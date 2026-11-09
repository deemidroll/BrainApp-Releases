# Brain downloads

Download Brain for an Apple silicon Mac running macOS 15 or later and connect it to Google Meet in Chrome.

## Current beta

- [Download Brain for Mac 0.5.20 (39)](https://github.com/deemidroll/BrainApp-Releases/releases/download/mac-0.5.20-39/Brain-0.5.20-39.zip)
- [Install the Chrome companion from the Chrome Web Store](https://chromewebstore.google.com/detail/brain-%E2%80%94-google-meet-conte/ahgkfkegjhimigcjlcnpfobjdcigacap)
- [Installation and connection instructions](INSTALL.md)
- [Release notes](https://github.com/deemidroll/BrainApp-Releases/releases/tag/mac-0.5.20-39)
- [SHA256 checksums](https://github.com/deemidroll/BrainApp-Releases/releases/download/mac-0.5.20-39/SHA256SUMS)

The Mac app is Developer ID signed, notarized and stapled. The Chrome companion is available from the Chrome Web Store. Meeting recording requires explicit opt-in and macOS microphone and screen/system-audio permissions.

## Verification

The direct Mac ZIP passed signature, notarization-ticket, extracted-archive and Gatekeeper checks with a quarantine marker. Its anonymous public download matched the verified artifact. Brain 0.5.20 (39) is also available through TestFlight. A separately identified release-code sandbox copy passed first-run folder creation, automatic companion connection, Disconnect and reconnection checks. Real-meeting acceptance for the direct ZIP remains open.

Automatic connection requires Chrome companion 0.1.8. If the Store offers 0.1.7, automatic setup will be available after its 0.1.8 update. Existing paired 0.1.7 connections can continue using saved credentials.

Whisper transcription runs entirely offline on the Mac. Brain never uploads audio or transcripts. A folder provider can synchronize Markdown notes when you choose a synchronized destination.

[Brain website](https://brain.dmdrll.com/) · [Privacy and support](https://brain.dmdrll.com/privacy)
