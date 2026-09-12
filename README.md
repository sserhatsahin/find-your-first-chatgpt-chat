# ChatGPT History Explorer

Find your oldest ChatGPT conversations in seconds — without waiting for a data export.

ChatGPT History Explorer runs directly in your browser while you're logged into ChatGPT. It intelligently searches your conversation history, estimates the end of the history using account age and conversation timestamps, and shows your oldest conversations in a classic ChatGPT-style interface.

## Features

- Finds the end of large ChatGPT histories with very few requests
- Works with accounts containing hundreds or thousands of conversations
- Uses your account creation period to optimize the search
- Shows your oldest conversations
- Opens conversations inside a classic ChatGPT-style reader
- Includes a direct link to open any conversation normally in ChatGPT
- Optional exact scan for verifying the oldest conversations
- No data export required
- No external server
- No API key required

## Usage

1. Open ChatGPT and make sure you're logged in.
2. Open your browser's Developer Tools.
3. Go to the Console tab.
4. Copy the contents of `history-explorer.js`.
5. Paste it into the Console and press Enter.
6. Wait for the scan to finish.

## Privacy

The script runs in your browser and communicates only with the ChatGPT endpoints already available to your logged-in session.

Do not share your access token, HAR files, exported ChatGPT data, account IDs, or conversation contents.

## Disclaimer

This is an unofficial project and is not affiliated with or endorsed by OpenAI.

It relies on undocumented/internal ChatGPT web endpoints, which may change at any time.

Only use it with your own ChatGPT account.
