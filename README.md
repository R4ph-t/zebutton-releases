# Ze Button

A physical push-to-talk button for your Mac, with local speech recognition.

[Download the latest installer](https://github.com/R4ph-t/zebutton-releases/releases/latest)

Requires an Apple Silicon Mac and macOS 15 or later. Python and the speech model are included. Transcription runs locally on your Mac.

## Install

1. Open the DMG and drag **Ze Button** into **Applications**.
2. Open Ze Button and enable its Accessibility permission when prompted.
3. Connect the button by USB and run Wi-Fi setup for the initial pairing.

The permanent app identifier is `com.raphaelterrier.zebutton`. When upgrading from 0.1.0, replace the app manually once and enable Accessibility again. Pairing data, recordings, and existing preferences are retained. Later updates use Sparkle normally; **Check for Updates…** is available from the app menu.

## Switch Macs wirelessly

With device firmware 0.8 or later, pair each Mac once by USB. On the button, open **Settings → Connection**, swipe to a saved Mac, and press to connect. The selected Mac must be running Ze Button and reachable over Wi-Fi.

**Disconnect Ze Button** in the Mac menu stops that Mac accepting connections, including after relaunch. **Connect Ze Button** makes it available again. Disconnection keeps pairing and recordings intact.

This public repository hosts installers and the update feed only. Application source is maintained privately.
