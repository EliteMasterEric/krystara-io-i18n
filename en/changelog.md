# Changelog

This page documents the major changes that have occurred with Eric's Gems of War Tools.

## Contents

1. [Version 1](#version-1)
2. [Version 2](#version-2)

## Version 1

- Base version, written in React + NodeJS in like 4 hours.
- Only support for PvP leaderboard.
- No language support, no platform support.
- No mobile compatible interface.

## Version 2

- Rewrote the app entirely over about a week.
- Now uses MaterialUI for styling, allowing compatibility with mobile.
- Added support for multiple platforms to all existing views.
- Added localization support (for all languages used by the game).
- Added dark mode theme support.
- Data fetcher now fetches 5 minutes before reset (to get accurate end-of-day leaderboard data) and 5 minutes after reset (to start recording early).
- Revamped [PvP Leaderboard](/pvp) view.
- Added [Current Tasks](/tasks) view.
- Added [Upcoming Events](/events) view.
- Added [Guild Leaderboard](/guild) view.
- Added [Guild Wars Brackets](/guildwars) view.
- Added **Changelog** view (this one).
- Added [Privacy Policy](/privacy) view.
- Improved performance and security using special headers.
- Preferred dark mode setting, platform, and language now saved to local storage.
- Added Google Analytics for improved page usage insights. See Privacy Policy for more info.
- Created [community localization project](https://github.com/MasterEric/gow-stuff-i18n).
