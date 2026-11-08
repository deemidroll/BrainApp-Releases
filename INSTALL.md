# Install Brain for Mac beta

This release includes Brain for Mac 0.5.15 (34) and the Brain Google Meet Chrome companion 0.1.7.

Requires an Apple silicon Mac with macOS 15 or later and Google Chrome.

## Install the Mac app

1. Quit your running copy of Brain.
2. Download [Brain-0.5.15-34.zip](https://github.com/deemidroll/BrainApp-Releases/releases/download/mac-0.5.15-34/Brain-0.5.15-34.zip) and unzip it.
3. Move `Brain.app` to Applications and open it. This app is Developer ID signed, notarized and stapled.

## Install the Chrome companion beta

The Chrome Web Store submission is being prepared. Use the ZIP for manual beta installation.

1. Download [Brain-Meet-Companion-0.1.7.zip](https://github.com/deemidroll/BrainApp-Releases/releases/download/mac-0.5.15-34/Brain-Meet-Companion-0.1.7.zip) and unzip it into a folder you will keep on this Mac.
2. Open `chrome://extensions` in the Chrome profile you use for Google Meet.
3. Disable older Brain companions and enable Developer mode.
4. Click **Load unpacked** and select the extracted folder containing `manifest.json`.
5. Keep that folder in place so Chrome can load the companion on later launches.

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

Quit Brain before replacing the app with a newer release. For a manually installed companion, unpack its update into the same extension folder and click **Reload** in `chrome://extensions`.

Run one copy of Brain at a time. The manual beta companion uses manual updates. The Chrome Web Store release will support Chrome-managed updates after publication.

## Verify downloads

Download [SHA256SUMS](https://github.com/deemidroll/BrainApp-Releases/releases/download/mac-0.5.15-34/SHA256SUMS) into the folder with both ZIPs and run `shasum -a 256 -c SHA256SUMS`.

[Brain website](https://brain.dmdrll.com/) · [Privacy and support](https://brain.dmdrll.com/privacy)
