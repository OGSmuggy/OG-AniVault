# OG AniVault

OG AniVault is a Windows desktop anime browser and player built with Tauri, React, and Vite.

## Features

- Browse anime from AnimeKai inside the app
- Watch episodes in the built-in player
- Switch Sub and Dub sources when available
- Live Top 10 lists for Today, Week, and Month
- Latest Episodes filters for All, Sub, Dub, Trending, and Random
- Fresh Releases, Recently Added, and Completed sections
- Estimated airing schedule
- Search and browse by genre, type, status, and A-Z
- Cover art fallback for missing posters

## Release Build

The GitHub release upload script publishes only the finished app files, not the source code.

Included release files:

- `OG AniVault.exe`
- Tauri installer files from the production build, when available
- This `README.md`

## Requirements

OG AniVault uses the Windows WebView2 runtime, which is included on most modern Windows installs. If the app does not open, install Microsoft Edge WebView2 Runtime from Microsoft.

## Notes

OG AniVault is a desktop shell that loads publicly available anime metadata and playback sources from external services. It does not host video content.
