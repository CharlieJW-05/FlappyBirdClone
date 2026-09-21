# Flappy — One Tap Arcade

A polished, single-file HTML5 arcade flyer built to feel like a native iOS game. Installable as a full-screen PWA, playable offline, no dependencies.

## Play

Live: https://charliejw-05.github.io/FlappyBirdClone/

On iPhone: open the link in Safari → Share → Add to Home Screen. It launches full-screen with its own icon and works offline.

## What's in it

Gameplay
- Fixed-timestep physics (120 Hz simulation, frame-rate independent) — plays identically on 60/120 Hz screens
- Circle-vs-rect collision with forgiving hitbox
- Smooth difficulty ramp: pipe speed, gap size, and spawn rate all scale with score
- Get Ready state with tap hint, death tumble animation, hit flash, screen shake

Presentation
- Retina-sharp canvas (devicePixelRatio-aware), phone-aspect letterbox on desktop
- Day → dusk → night → dawn sky cycle with stars, sun glow, and moon
- Parallax hills, drifting clouds, scrolling striped ground
- Squash-and-stretch bird with animated wing, particles on flap and crash
- Animated menu, sliding game-over panel with medal disc

iOS-quality details
- Safe-area aware layout (notch/home indicator), no double-tap zoom, no scroll bounce
- Haptic feedback on flap, score, and crash (where supported)
- Auto-pause when the app is backgrounded
- Web Share: long-press your score on game over to challenge friends
- Sound synthesized with Web Audio (flap, ding, crash, medal fanfare); mute persists
- Procedural chiptune background music (112 bpm loop, synthesized live — no audio files)
- Settings panel (gear icon) with separate music and sound-effects toggles, saved between sessions

Progression
- Medals: Bronze 10 · Silver 20 · Gold 30 · Platinum 40
- Best score, games played, and average score persist in localStorage (migrates old saves)

## Controls

- Tap / click / Space / Up arrow — flap
- P or Esc — pause
- Buttons top-right — sound and pause

## Files

- `index.html` — the whole game
- `manifest.webmanifest`, `sw.js`, `icon.svg` — PWA install + offline support

## License

MIT
