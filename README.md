# MG4CPlay

MG4CPlay brings wireless CarPlay to compatible MG4 infotainment systems.

## Compatibility

- Verified on an MG4 head unit running SWI69 and Android 9.
- Other MG4 software and hardware revisions may work, but have not yet been verified.
- This is an independent community project and is not affiliated with or endorsed by MG or Apple.

## Installation

1. Download [MG4CPlay 0.2.9-mg4.37](https://github.com/fatihdonmezdev/MG4-Wireless-Carplay/raw/main/downloads/MG4CPlay-v0.2.9-mg4.37.apk), or check [Releases](https://github.com/fatihdonmezdev/MG4-Wireless-Carplay/releases/latest) for newer builds.
2. Copy the APK to the vehicle head unit.
3. Allow installation from unknown sources when Android asks, then install the APK.
4. Open **MG4CPlay** and grant the requested Bluetooth, nearby-device, location and microphone permissions.
5. Enable the vehicle hotspot, preferably on 5 GHz.
6. Pair the iPhone with the vehicle over Bluetooth.
7. In MG4CPlay, enter the vehicle hotspot name and password, then select **Connect phone**.
8. Accept the CarPlay prompts on the iPhone.

If Android reports that the app was not installed because an older build has a different signature, remove that incompatible build first and install this APK again. Removing it also clears its saved settings.

## Hybrid Bluetooth audio

Version 0.2.9-mg4.37 uses CarPlay for the screen, touch input and media controls, while music remains on the MG factory Bluetooth/A2DP connection. CarPlay audio output is intentionally not advertised, avoiding the packet loss and repeated audio skips seen on the head unit's wireless CarPlay path.

Pair the iPhone with the MG Bluetooth system and select the vehicle's Bluetooth audio source. Spotify and other music apps should no longer offer CarPlay as an audio destination while the CarPlay interface remains available.

## Notes

- Keep Bluetooth and Wi-Fi enabled on the iPhone.
- The package is built for Android 9 or newer.
- Video playback support depends on iOS, the media source and vehicle state. DRM-protected services may not work.
- Compatibility with every MG4 firmware version is not guaranteed.

## Credits and licenses

MG4CPlay is maintained by [fatihdonmezdev](https://github.com/fatihdonmezdev).

The receiver is derived from [xcertplay](https://github.com/shilapi/xcertplay), licensed under GPL-3.0. Interface work is derived from [DiAuto](https://github.com/shihabal3amri/DiAuto), licensed under AGPL-3.0. Their copyright and license notices remain applicable. Corresponding source for distributed builds is retained in the private development repository and can be provided on request.

CarPlay and the CarPlay icon are trademarks of Apple Inc.
