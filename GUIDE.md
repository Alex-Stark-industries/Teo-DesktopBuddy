# Guide

Everything Teo does, and everything you can type to him. Every quick action
runs instantly — no thinking, no waiting on a model — and every reply is
spoken aloud (unless you turn the voice off) as well as shown in the bubble.

## Ways to talk to Teo

| You do | Teo does |
|---|---|
| **Click** him | Hops and smiles. |
| **Double-click** him | Opens the toolbox bubble (a type-box and all the tools). |
| **Right-click** him | Opens the quick settings (see below). |
| **Drag** him and let go | Empty desktop: falls back to the taskbar and stays there. A window's **side edge**: grabs the wall and climbs to the top. **Over** a window: hops onto its top edge. |
| **Open a window or folder** | Walks over, jumps, climbs and perches on its top edge, with a bubble of quick actions. |
| **Close the window he's on** | Slips off and goes home. |
| **Press × (or Esc)** on the bubble | Closes it — and stops him talking at once. |

He is calm on purpose: a few seconds between automatic climbs, a new window can call
him away from an old one unless you're using his bubble, the bubble fades by itself,
and he hides while a video or game is fullscreen. If he doesn't climb a window,
`.desktopbuddy\buddy.log` in your user folder says why.

## On a folder

| Action | What it does |
|---|---|
| **What's inside?** | Speaks how many files and folders it holds, their total size, and the newest item. |
| **Copy path** | Copies the folder's path to your clipboard. |
| **Search the web** | Opens your browser with a search for the folder's name. |
| **Tools ▸** | The toolbox (below). |

## On any other window

**Search the web** (for the window's title) and **Tools ▸**.

## On Google or YouTube

Open the home page of **Google** or **YouTube** in Chrome, Edge, Firefox, Brave, Opera or Vivaldi. Teo climbs up, hops onto the search box and asks what
you're looking for. Type it in his bubble and he opens the results. (He only uses the window title and the position of the
search box — never what you type on the page or anything else in it.) *No thanks* sends him home.

## Quick settings (right-click)

| Setting | What it does |
|---|---|
| **Quiet mode** | For one hour Teo won't climb on his own or give tips; a little "z z" shows. It ends by itself. Timers and reminders still ring. |
| **Voice: On/Off** | Speak answers out loud or stay silent. You can also choose when you start him: launch with `--voice=off` or `--voice=on` (add it to the shortcut's *Target*). |
| **Tips: On/Off** | The little life tips. |
| **Give me a tip** | A tip right now. |
| **Start with Windows: On/Off** | Whether Teo starts when you log in. Off by default — he never turns it on by himself. |
| **Climb on this window** | Sends him to the window in front. |
| **About** | A short spoken introduction, including the version number running. |
| **Quit** | Closes him completely. |

## Little tips

When you've been at the PC for a while without a 5-minute break, and Teo is resting at home, he may pop a
bubble — drink some water, stand up and stretch, rest your eyes, "you just started, keep going!", or go to bed when it's very late.
At most one every 25 minutes; never in Quiet mode, never while you're in a fullscreen video.

## Pocket assistant (type in the bubble)

| You type | What happens |
|---|---|
| `timer 10 min` · `set a timer for 1 hour 30 minutes` · `timer 45 seconds pasta` | Starts a timer; he rings (voice + bubble) when it's done. |
| `remind me in 20 minutes to stretch` · `remind me to call Sam at 3pm` · `remind me at 15:30 to leave` | A reminder at that time. |
| `timers` · `cancel timers` | Lists or cancels what's pending. |
| `note buy milk` · `remember that the code is 4821` | Saves a quick note on your PC. |
| `notes` · `clear notes` | Shows your latest notes, or deletes them (after asking). |
| `15% of 80` · `12*8` · `(2+3)*4` · `100 divided by 8` | Does the math. |

Timers and reminders survive a restart, and still ring in Quiet mode. Everything is stored only on your PC.

## Tools ▸

| Tool | What it does |
|---|---|
| **Time** · **Date** | Speaks the time or today's date. |
| **Battery** | Your battery percentage (laptops only — otherwise an honest "no battery detected"). |
| **System** | How much memory is in use and how long the PC has been running. |
| **What's running** | The names of apps currently open with a visible window. |
| **Weather…** | Type a city and he speaks the temperature and conditions. |
| **News** | The latest headline from NASA, the Federal Reserve, NIST, the Department of Labor and NOAA, naming the sources. |
| **Volume + / −** | One notch up or down, like your keyboard's volume key. |
| **Open…** | Type the name of any installed app (or folder, or web address) and he opens it. If nothing is found, he tells you. |
| **Timer… / Remind me… / Note… / My notes / Calculate…** | The pocket assistant above. |

You can also type short phrases instead of pressing buttons: `time`, `battery`, `weather rome`, `open notepad`, `search cats`, `volume up`, `news`.

---

### Why only U.S. government sources for News?

Newspaper RSS feeds (BBC, the New York Times, and nearly every other major
outlet checked) restrict their feeds to personal, non-commercial use, which
a product that may be sold can't honor. Works published by the U.S.
federal government carry no copyright at all (17 U.S.C. §105), so they're
free to read aloud without a license. That trade-off means a narrower topic
range — science, economic data, technology — instead of general-interest
news, but it's the one combination that's actually free to use.
