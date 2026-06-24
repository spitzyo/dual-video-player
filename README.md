# Dual Video Player

Play two clips **side by side, perfectly in sync** — one timeline, one speed, one audio source. Runs entirely in your browser. Nothing is uploaded.

## Open it
Double-click `index.html`. No install, no build, no dependencies.

## Load videos — two ways
1. **Library folder** — *Open library folder* → pick a folder.
   Any sub-folder holding **2 clips** = a pair. Nested folders become categories in the sidebar. Click a pair to load it.
2. **Two clips directly** — *Load two clips* → ⌘-click any two files.

Left clip = **L**, right clip = **R**.

## Controls

| Key | Action |
|----|----|
| `Space` / click a video | Play / pause |
| `←` / `→` | Back / forward 10 s |
| `,` / `.` | Step one frame |
| `§` then `1`–`9`, `0` | Speed: 1.0, then 1.1–1.9, 2.0 |
| `A` | Switch audio L ↔ R |
| `S` | Swap the two sides |
| `R` | Reload the current pair |
| `F` | Fullscreen |
| `L` | Show / hide sidebar |

Also: **drag the boundary** between the videos to resize them, **click or drag the timeline** to seek, and the **15m** button skips 15 minutes ahead.

## Good to know

- **Auto audio pick** — when one clip is silent and the other isn't, it starts on the one with sound. This needs the browser's audio-track info, which is reliable in **Safari**. In Chrome/Firefox it may not auto-switch, but the **L / R** button always works manually.
- **File types** — standard **MP4 (H.264)** and **MOV** play in every browser. Unusual codecs/containers (e.g. some `.mkv`) may not decode — that's usually a browser limit.
- **You re-pick the folder each session.** Browsers don't grant a web page lasting access to the hard drive, so the library isn't remembered between visits.
- **Pairs are folders with 2 clips.** If there are more than two, it uses the first two alphabetically.

### Why the limits?
This is intentionally a single, offline, dependency-free file that behaves the same everywhere and never talks to a server. To keep it lightweight, versatile, and stable, a few UI conveniences were traded away on purpose — most notably re-choosing the folder each time, and audio auto-detection only where the browser allows it.
