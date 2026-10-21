# Privacy

Short version: **Teo (Desktop Buddy) collects nothing.** No account, no analytics,
no telemetry, no crash reporting, nothing sent to us, ever. It has no usage
limits and needs no subscription of any kind (AI-assistant or otherwise).

## How Teo knows about your windows

A tiny helper program (`winwatch.exe`) asks
Windows which windows are open and where. It reads only each window's
**title, type, program name, position and size** — and, for File Explorer
folder windows, the folder's path. It never reads what is *inside* a window,
never sees keystrokes, and has no network access. Nothing it sees is stored
or sent anywhere.

**Search boxes.** When a browser window's title shows Google's or YouTube's home page, Teo asks the
browser — through Windows' built-in accessibility layer, the same one screen readers use — where its
search box is. That reads the field's name and position only, never what is typed or anything else on
the page, and only for that one window. (Browsers switch on their page-accessibility tree when asked,
which can use a little extra memory in that browser until it is restarted.)

## What reaches the internet (only when you ask, or for updates)

| When | What happens |
|---|---|
| **First speech, only if no voice model exists on the PC** | Downloads the open-source Kokoro voice model once (~300 MB). If Lumen is installed, its copy is re-used instead and nothing is downloaded. Afterwards speech is fully offline. |
| **On launch, then hourly** | Checks this project's GitHub releases for a newer version and installs it quietly. Nothing about you is sent. |
| **Weather…** | The city you type is sent to [Open-Meteo](https://open-meteo.com/) (free, keyless public API). |
| **Search the web** | Your default browser opens a DuckDuckGo search for the window/folder title or the words you typed — exactly as if you had typed it yourself. |
| **News** | Fetches five U.S. federal-government RSS feeds (NASA, Federal Reserve, NIST, Dept. of Labor, NOAA). No personal data is sent. |

Everything else — time, date, battery, system status, what's running, volume,
opening apps, folder contents, copying a path, tips, timers, reminders, notes and
math — happens entirely on your PC.

## What Teo stores

Only `~/.desktopbuddy/settings.json` (Quiet mode, voice and tips on/off, where you
parked Teo on the taskbar, plus the timers, reminders and notes you asked him to keep — all
only on your PC), a small `buddy.log` with start-up and update
messages and the names of windows he climbed on (to help diagnose problems —
it never leaves your PC; delete it any time), and the voice model if it had
to be downloaded.
