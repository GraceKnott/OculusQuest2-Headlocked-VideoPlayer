# Head-Locked Video & Visuals

A browser-based head-locked video player and collection of visual studies, made for WebXR headsets.

[**Open the Visual Preview**](https://graceknott.github.io/OculusQuest2-Headlocked-VideoPlayer/visual-preview.html)

> For immersive mode, use a WebXR-capable headset browser over HTTPS. You can also browse the visuals on desktop or mobile.

## What’s inside

- **Head-locked VR** — pins the selected visual to your view
- **Audio ambience** — local audio files with volume control
- **Local Video Player** — plays a video selected from your device

## Using the visual preview

1. Open the preview link and select a visual.
2. Open the small controls button.
3. Adjust the speed, message timing, or ambience.
4. Choose **Enter head-locked VR** in a supported headset browser.

Tap **Start ambience** to enable audio; browsers require a user action before playing sound.

## Audio

Audio files are stored in [`audio/`](./audio/). See [`audio/CREDITS.md`](./audio/CREDITS.md) for sources and licenses.

## Compatibility

The regular preview works in modern browsers. Immersive mode requires WebXR support and a secure HTTPS connection. Audio may need to be started manually.
Meta quest browser is compatible with [**Local Video Player**](https://graceknott.github.io/OculusQuest2-Headlocked-VideoPlayer) wheras [**Visual Studies**](https://graceknott.github.io/OculusQuest2-Headlocked-VideoPlayer/visual-preview.html) is only possible through the [**Wolvic Browser**](https://www.wolvic.net/en/).

## Project files

- [`index.html`](./index.html) — Local Video Player
- [`visual-preview.html`](./visual-preview.html) — Visual studies
- [`audio/`](./audio/) — Audio files and credits
