# KEEP IT TOGETHER 😐

**[PLAY NOW](https://ashleywolf.github.io/keep-it-together/)** (keep a straight face, we dare you)

Your webcam watches your face. We try to make you smile. The longer you last, the harder we try.

## How it works

Your webcam calibrates to your resting face. Then the provocations start: developer jokes, absurd scenarios, visual effects warping your own video feed. Any twitch, smirk, or grin fills your composure meter. Hit 100% and it captures your shame photo.

**Round 1** (0-15s): Developer humor. You've been unmuted for 20 minutes eating chips. Your code compiles on the first try. A pigeon gives status updates.

**Round 2** (15-30s): Absurd scenarios + your video starts wobbling and stretching.

**Round 3** (30-45s): Chaos. Rainbow filters, squash effects, the provocations get weirder.

**Round 4** (45s+): The game breaks the fourth wall. "DON'T THINK ABOUT SMILING. DON'T THINK ABOUT NOT THINKING ABOUT SMILING."

When you crack, it captures your face mid-laugh and rates your composure.

## Tech

19KB. One HTML file. No build step. No dependencies to install.

- [TensorFlow.js + BlazeFace](https://github.com/nicolo-ribaudo/face-mesh) for face detection
- Canvas pixel differencing for expression change detection
- Web Audio API for sound effects
- CSS animations for visual provocations

## Run locally

```bash
python3 -m http.server 8000
open http://localhost:8000
```

Camera needs HTTPS or localhost.

## License

MIT
