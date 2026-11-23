# Lecture Player

Play two videos **side by side, perfectly in sync**: one timeline, one speed control, one audio track. A single video plays on its own with the same controls. It runs entirely in your browser. Nothing is uploaded and there's nothing to install.

**Open it:** **https://spitzyo.github.io/lecture-player/**

## What it's for

Any two recordings of the same moment:

- **Lectures and talks:** the speaker's camera next to the slides or screen.
- **Two camera angles:** a match, a rehearsal, an experiment.
- **Practice:** your dance, music or sports take next to the reference video.
- **Comparisons:** two takes, two edits, or before and after.
- **Tutorials:** a screen recording next to the webcam.

## Get started

1. Open the link above, or download `index.html` and double-click it. It works offline.
2. Load your videos in one of two ways:
   - **Load videos:** pick one video, or ⌘-click (Ctrl-click on Windows) two, plus a caption file if you have one.
   - **Open library folder:** pick a folder. Every sub-folder that holds one or two videos becomes an entry: one video plays alone, two play side by side. A folder of entries becomes a group you can open and close, and a folder of folders becomes a small heading. Click an entry to play it.
3. Press **Space** to play.

The left video is **L** and the right one is **R**.

## Features

- **True sync:** both videos follow one timeline. If they drift apart, only the muted video is nudged back, so the sound you hear never stutters.
- **One audio track:** pick L or R under **⋯** (or press `A`), or click the speaker to mute both. When only one video has sound, it's picked for you automatically (Safari).
- **Captions:** if a video's folder also holds an `.srt` or `.vtt` caption file, a **CC** button appears. Captions show at the bottom of the video you're listening to, and right-to-left languages like Hebrew display correctly. Automatic captions that repeat each line on the next one show each line only once.
- **Fine speed control:** from 0.1× to 3× (2× in Safari), with voices kept at their natural pitch. Use the 1×, 1.5× and 2× buttons or the number keys, or click the speed value and use the arrow keys for 0.05× steps.
- **Timeline previews:** while dragging the timeline, hold still for a moment to see both videos at that point.
- **Zoom and pan:** scroll on a video to zoom in where your pointer is, then drag to look around.
- **Lighten:** the ☀ button in a video's corner brightens dark footage, such as a blackboard.
- **Layout:** drag the divider between the videos to resize them, or swap sides under **⋯** (or press `S`).
- **Fullscreen:** press `F`, click the button, or double-click a video. The sidebar and controls tuck away and slide back when you move the pointer to the edge.
- **Next video:** in the last 10 seconds, a small **Next** button appears in the corner of the video. It plays the entry listed below the current one in the same sidebar folder. The 10 seconds are real time, so at 2× it appears 20 seconds of video before the end.
- **Reload:** under **⋯** (or press `R`), restarts the video files and keeps your place, speed and audio choice.
- **Library sidebar:** stays out of the way while you watch. Move the pointer to the left edge of the window (a small tab shows as you near it), or press `L`, and it slides in over the videos without resizing them. A name like `12345 2026-11-10 Lesson 2` shows as "Lesson 2", with "Tue 10 Nov" and its length under it, and a numbered name like `01 - Unit 8.1: Overview` shows as "8.1 Overview".
- **Progress and resume:** a ✓ marks what you've watched, a red line shows how far you got, and each group counts its watched entries. Reopening a video continues where you stopped, with a **Start over** button for a few seconds. Reaching the last few minutes or seconds counts as watched.
- **Long names:** hover a clip or folder name that's cut off to see it in full. The name also slides sideways so you can read it in place.

## Controls

| Key | Action |
|---|---|
| `Space` or click a video | Play / pause |
| `←` / `→` | Back / forward 10 seconds |
| `` ` `` or `§` | Speed 1× |
| `1`–`9` | Speed 1.1× – 1.9× |
| `0` | Speed 2× |
| Click the speed value, then `←` / `→` | Speed −/+ 0.05× (hold `⇧` for 0.10×). Your next click anywhere else, or `Esc`, turns the arrows back to skipping time |
| `A` | Switch audio L ↔ R (two videos) |
| `M` | Mute / unmute |
| `C` | Captions on / off |
| `S` | Swap sides (two videos) |
| `R` | Reload the video(s) |
| `N` | Next video (while the Next button shows) |
| `F` | Fullscreen |
| `L` | Show / hide the sidebar |
| `?` | Show all shortcuts |

**Mouse:** click a video to play or pause, and double-click it for fullscreen. Scroll on a video to zoom in where your pointer is, and drag to pan. While zoomed in, a double-click resets the zoom instead of going fullscreen. Click or drag the timeline to jump. The **15m** button skips 15 minutes ahead.

## Privacy

Your videos never leave your computer. The player is a single page with no accounts, no tracking and no server. Once it has loaded, it makes no network requests at all. What you've watched is saved in your browser's own storage on this computer, never in your files.

## Limits

- **Made for computers:** use Safari, Chrome, Edge or Firefox on a Mac, Windows or Linux computer. Phones and tablets can't open a folder of videos.
- **One or two videos at a time.**
- **Both videos need to start at the same moment.** There's no setting yet to shift one of them in time.
- **You pick the folder again each visit,** because browsers don't let a web page keep access to your files.
- **Progress stays with one browser and one address:** the online page and a copy saved on your computer each keep their own, and clearing the browser's site data clears it.
- **Automatic audio pick works best in Safari.** Other browsers may not report which video has sound, but the L / R buttons always work.
- **Safari tops out at 2×.** Above that speed, Safari shows only an occasional frame while the sound keeps going, so the player stops at 2× there. Other browsers go up to 3×.
- **File types:** MP4 (H.264) and MOV play in every browser. Some MKV files or unusual formats may not play, which is a browser limit.
- **Folders with three or more videos:** videos of the same length (within a second) play as a pair, and the rest play alone.

## Why it's built this way

One small file with no dependencies behaves the same everywhere and never talks to a server. A few conveniences, like remembering your folder or detecting audio in every browser, were given up on purpose to keep it that way.

## License

MIT
