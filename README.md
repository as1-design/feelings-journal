# 🫧 Feelings journal

An evening check-in: choose the feelings that filled the day, write when, why and what you thought, and see where they lived in the body through the seven chakras.

[Open](https://as1-design.github.io/feelings-journal/)

## Files to upload (all in the repository root)

| File | What it is |
|---|---|
| `index.html` | the app |
| `manifest.json` | lets the phone install it |
| `sw.js` | makes it work offline (change `CACHE` on every upload) |
| `icon-192.png`, `icon-512.png` | home-screen icons |
| `garden/` (folder, 43 pictures) | the painted garden: one picture per season and time of day, plus the visitors, flowers, walkers, boat and lanterns. Upload the whole folder. |
| `apps-script.gs` | the Google Sheet connector (pasted into Apps Script, not used by the page) |

## Google Sheet (optional)

Settings › Google Sheet › "How to set it up" walks through it: new Sheet › Extensions › Apps Script › paste the script › set your passphrase › Deploy as a web app (Execute as: Me, Access: Anyone) › paste the URL and passphrase into the app on each device.

Entries are always saved on the device first and synced when online.
