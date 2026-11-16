# YouTube Auto Ad Skipper

A lightweight, Manifest V3 browser extension that automatically detects and skips YouTube video ads in real time.

## Features

- **Instant Ad Skipping:** Automatically clicks YouTube's skip buttons (`.ytp-ad-skip-button`, `.ytp-ad-skip-button-modern`, `.ytp-skip-ad-button`) the moment they appear.
- **Unstoppable Ad Fast-Forward:** Accelerates unskippable ad playback to `16.0x` speed, mutes audio, and jumps to the end of the ad stream.
- **Zero Performance Overhead:** Uses a native `MutationObserver` to monitor DOM changes efficiently without constant polling intervals.
- **Manifest V3 Compliant:** Built using modern Chrome extension architecture standards with minimal permissions (`activeTab`).

## Project Structure

```text
youtube-ad-skipper/
├── manifest.json    # Extension configuration and permissions (Manifest V3)
├── content.js       # Core DOM observer and ad-bypassing logic
└── README.md        # Project documentation
Installation (Load Unpacked)
Clone or Download this Repository:
git clone [https://github.com/vignan2025/youtube-ad-skipper-ext.git](https://github.com/vignan2025/youtube-ad-skipper-ext.git)

Open Chrome Extensions:
Navigate to chrome://extensions/ in Google Chrome (or any Chromium-based browser like Brave or Edge).
Enable Developer mode using the toggle in the top-right corner.
Load the Extension:
Click Load unpacked in the top-left corner.
Select the extracted youtube-ad-skipper project folder.
Ensure the extension toggle is switched ON, then refresh any open YouTube tabs.
