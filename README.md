# Anime Society of LCCC

The website for the Anime Society of Lorain County Community College.

The whole site is a single page, `index.html`, with its images in the `assets` folder. There is nothing to build or install: open `index.html` in a browser to view it.

## What's on the site

- **About Us:** welcome, what the club does, and the officers (click an officer to read their About Me).
- **Club Info** (a dropdown menu with three pages):
  - **Club Info:** meeting details, the anime wheel and current watch list, summer plans, yearly events, rules, and how to join.
  - **Announcements:** live #announcements from Discord.
  - **Calendar:** club nights, off weeks, breaks, and holidays.
  - **Constitution:** opens `assets/ASLC3-Constitution-2026-2027.pdf` in a new tab. For a new year, add the new PDF to `assets` and update the two links to it in `index.html` (search for `Constitution`).
- **Contact:** the live #rules channel from Discord, Instagram, and LCCC Connect.

The Discord channels are embedded with [WidgetBot](https://widgetbot.io). To show a different channel, change the last number in the embed's link to that channel's ID.

## Common updates

All of these are in `index.html`. Search the file for the text in quotes to find the right spot.

| To change | Look for |
| --- | --- |
| Anime list and episode numbers | `On The Wheel This Semester` |
| Officers and their About Me | `===== OFFICERS =====` |
| Club dates, off weeks, and breaks | `===== CALENDAR =====` |
| Snow and Christmas lights on page load | `HOLIDAY_SECONDS` (set to `0` to turn off) |

Officer profile pictures and favorite anime pictures go in the `assets` folder.
