# Raja Snake

Raja Snake is a login-free, offline-first canvas game. The playable app is a single `index.html` file with no backend, Firebase, build step, or runtime dependencies.

## Features

- Solo and two-player local play on the same device
- 100 levels with increasing difficulty, speed, and obstacles
- Scores, best run, XP, and coins
- Unlockable board themes and snake styles
- Keyboard and touch controls, sound, and responsive layout
- Progress saved in this browser with `localStorage`

Progress is local to one browser/device; it does not sync to other devices. Local coins are game points, not a secure real-money wallet.

## Run locally

Open `index.html` directly, or serve this folder:

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.

## Publish

Upload `index.html` to any static website host. For GitHub Pages:

1. Put `index.html` in the root of a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Select **Deploy from a branch**, choose the branch and `/ (root)`, then save.
4. GitHub Pages will show the published HTTPS address in the Pages settings.

The game itself never asks players to sign in. Publishing through GitHub Pages still requires a GitHub account for the person who owns and publishes the repository.
