# 🐦 Flappy Bird

<div align="center">

![Flappy Bird](https://img.shields.io/badge/Flappy-Bird-73bf2e?style=for-the-badge&logo=gamepad&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla-JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-73bf2e?style=for-the-badge)

**A faithful recreation of the classic Flappy Bird with retro pixel aesthetics & synthesized sound effects.**

[▶ Play Now](https://alfredang.github.io/flappy-bird-game/)

</div>

---

## 📸 Screenshots

<div align="center">

### Start Screen
![Start Screen](screenshots/start-screen.png)

### Gameplay
![Gameplay](screenshots/gameplay.png)

### Game Over
![Game Over](screenshots/game-over.png)

### Mobile
<img src="screenshots/mobile-start.png" width="250" alt="Mobile Start"> &nbsp; <img src="screenshots/mobile-gameplay.png" width="250" alt="Mobile Gameplay">

</div>

## ✨ Features

- **Classic Flappy Bird style** — blue sky, green pipes, puffy clouds, city skyline
- **Cute animated bird** — orange body, flapping wing, red beak, expressive eye
- **Green pipes with caps** — highlights, shadows & outlines just like the original
- **Sound effects** — synthesized via Web Audio API (flap, score, hit, death)
- **High score tracking** — persisted in localStorage
- **Mobile responsive** — tap to flap, optimized portrait layout
- **Retro pixel font** — Press Start 2P for authentic arcade feel
- **Mute toggle** — sound on/off button
- **Zero dependencies** — single HTML file, no frameworks

## 🎮 Controls

| Platform | Action |
|----------|--------|
| Desktop | `Space` / `↑` / Click to flap |
| Mobile | Tap anywhere to flap |

## 🖼️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 Canvas | Game rendering |
| Vanilla JavaScript | Game logic & physics |
| Web Audio API | Synthesized sound effects |
| CSS3 | UI overlay & retro styling |
| GitHub Actions | Auto-deployment to Pages |

## 🏗️ Architecture

```
flappy-bird-game/
├── index.html              # Complete game (single file)
├── screenshots/            # Playwright-captured screenshots
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages deployment
└── README.md
```

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/alfredang/flappy-bird-game.git

# Open in browser
open index.html
```

No build step needed — it's a single HTML file.

## 📝 License

MIT
