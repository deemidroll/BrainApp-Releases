# Install Brain for Mac beta

This release includes Brain for Mac 0.5.19 (38) and the Brain Google Meet Chrome companion 0.1.7.

Requires an Apple silicon Mac with macOS 15 or later and Google Chrome.

## Install the Mac app

1. Quit your running copy of Brain.
2. Download [Brain-0.5.19-38.zip](https://github.com/deemidroll/BrainApp-Releases/releases/download/mac-0.5.19-38/Brain-0.5.19-38.zip) and unzip it.
3. Move `Brain.app` to Applications and open it. This app is Developer ID signed, notarized and stapled.

## Install the Chrome companion

1. Open [Brain — Google Meet context in the Chrome Web Store](https://chromewebstore.google.com/detail/brain-%E2%80%94-google-meet-conte/ahgkfkegjhimigcjlcnpfobjdcigacap) in the Chrome profile you use for Google Meet.
2. Click **Add to Chrome** and confirm **Add extension**.
3. Open the Chrome Extensions menu and choose **Brain — Google Meet context**.

If you previously installed the companion with **Load unpacked**, remove that copy in `chrome://extensions` before installing the Store version, then connect it to Brain again using the steps below.

## Connect Chrome to Brain

1. Open Brain Settings and choose **Connect Chrome Extension**.
2. Copy the temporary code.
3. Open the Brain extension in Chrome, choose **Connect to Brain** and paste the code.
4. Allow the requested connection to `127.0.0.1` on your Mac.
5. Confirm **Connected** in both Brain and the extension.

## Enable meeting recording

Enable **Automatically record Google Meet** in Brain Settings when you are ready. Grant the microphone and screen/system-audio recording access requested by Brain.

Join a Google Meet call and check the visible recording indicator. Refresh and rejoin to test continuity, then leave the call and review the locally processed meeting.

## Update

If you already use TestFlight, update Pinky Brain there. Use one distribution channel and run one copy of Brain at a time.

Quit Brain before replacing the app with a newer release. Run one copy of Brain at a time.

Chrome manages updates for the companion installed from the Chrome Web Store. For a manually installed companion, unpack its update into the same extension folder and click **Reload** in `chrome://extensions`.

## Verify downloads

Compare the output of `shasum -a 256 Brain-0.5.19-38.zip` with its matching entry in [SHA256SUMS](https://github.com/deemidroll/BrainApp-Releases/releases/download/mac-0.5.19-38/SHA256SUMS).

[Brain website](https://brain.dmdrll.com/) · [Privacy and support](https://brain.dmdrll.com/privacy)
