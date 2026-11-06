# Dual Video Player

Play two videos **side by side, perfectly in sync**: one timeline, one speed control, one audio track. It runs entirely in your browser. Nothing is uploaded and there's nothing to install.

**Open it:** **https://spitzyo.github.io/dual-video-player/**

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
   - **Load two clips:** ⌘-click (Ctrl-click on Windows) two video files.
   - **Open library folder:** pick a folder. Every sub-folder that holds two videos becomes a pair, and nested folders become categories in the sidebar. Click a pair to play it.
3. Press **Space** to play.

The left video is **L** and the right one is **R**.

## Features

- **True sync:** both videos follow one timeline. If they drift apart, only the muted video is nudged back, so the sound you hear never stutters.
- **One audio track:** choose L or R, or click the speaker to mute both. When only one video has sound, it's picked for you automatically (Safari).
- **Fine speed control:** from 0.1× to 3×, with voices kept at their natural pitch. Use the 1×, 1.5× and 2× buttons or the number keys, or click **speed** and use the arrow keys for 0.05× steps.
- **Timeline previews:** while dragging the timeline, hold still for a moment to see both videos at that point.
- **Zoom and pan:** scroll on a video to zoom in where your pointer is, then drag to look around.
- **Lighten:** the ☀ button in a video's corner brightens dark footage, such as a blackboard.
- **Layout:** drag the divider between the videos to resize them, or swap sides with one click.
- **Fullscreen:** the sidebar and controls tuck away and slide back when you move the pointer to the edge.
- **Reload pair:** restarts both files and keeps your place, speed and audio choice.

## Controls

| Key | Action |
|---|---|
| `Space` or click a video | Play / pause |
| `←` / `→` | Back / forward 10 seconds |
| `` ` `` or `§` | Speed 1× |
| `1`–`9` | Speed 1.1× – 1.9× |
| `0` | Speed 2× |
| Click **speed**, then `←` / `→` | Speed −/+ 0.05× (hold `⇧` for 0.10×). Your next click anywhere else, or `Esc`, turns the arrows back to skipping time |
| `A` | Switch audio L ↔ R |
| `M` | Mute / unmute |
| `S` | Swap sides |
| `R` | Reload the pair |
| `F` | Fullscreen |
| `L` | Show / hide the sidebar |
| `?` | Show all shortcuts |

**Mouse:** scroll on a video to zoom, drag to pan, and double-click to reset the zoom. Click or drag the timeline to jump. The **15m** button skips 15 minutes ahead.

## Privacy

Your videos never leave your computer. The player is a single page with no accounts, no tracking and no server. Once it has loaded, it makes no network requests at all.

## Limits

- **Made for computers:** use Safari, Chrome, Edge or Firefox on a Mac, Windows or Linux computer. Phones and tablets can't open a folder of videos.
- **Two videos at a time.**
- **Both videos need to start at the same moment.** There's no setting yet to shift one of them in time.
- **You pick the folder again each visit,** because browsers don't let a web page keep access to your files.
- **Automatic audio pick works best in Safari.** Other browsers may not report which video has sound, but the L / R buttons always work.
- **File types:** MP4 (H.264) and MOV play in every browser. Some MKV files or unusual formats may not play, which is a browser limit.
- **A pair is a folder with two videos.** If a folder holds more, the first two in alphabetical order are used.

## Why it's built this way

One small file with no dependencies behaves the same everywhere and never talks to a server. A few conveniences, like remembering your folder or detecting audio in every browser, were given up on purpose to keep it that way.

## License

MIT
