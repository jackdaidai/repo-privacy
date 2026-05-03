# Caption Grab — Privacy Policy

**Last updated:** May 3, 2026

Caption Grab is a Chrome extension that captures and exports live captions from Google Meet and transcripts from Vimeo. This policy describes how the extension handles data.

## Data Collection

Caption Grab does **not** collect, transmit, or store any user data on external servers. All processing happens entirely within the user's browser.

Specifically, the extension:

- **Reads** caption text already rendered in the browser DOM on Google Meet and Vimeo pages
- **Stores** transcript text locally in `chrome.storage.local` so it persists across page refreshes
- **Stores** user preferences (export format, debounce timing, filename prefix) in `chrome.storage.sync`
- **Saves** exported transcript files (.txt, .json, .md) to the user's local filesystem via `chrome.downloads`

## What We Do NOT Do

- No data is sent to any external server or API
- No third-party transcription service is used
- No bot or external account joins meetings
- No audio is captured or recorded
- No personal information is collected
- No analytics or tracking is used
- No cookies are used

## Third-Party Services

The extension includes a bundled copy of the [Vimeo Player JS API](https://github.com/vimeo/player.js) (MIT license) for interacting with the Vimeo player. This library runs entirely within the browser and does not communicate with any third-party service beyond the Vimeo page already loaded in the user's tab.

## Data Retention

All data is stored locally on the user's device. The extension does not retain any data after the user clears it via the extension's "Clear" button or clears browser data through Chrome's settings.

## Contact

For questions about this privacy policy, please open an issue on the extension's GitHub repository or contact the developer through the Chrome Web Store listing.

## Changes

This policy may be updated from time to time. Any changes will be reflected in the "Last updated" date above.
