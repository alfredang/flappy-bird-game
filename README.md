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

| Title Screen | Get Ready | Gameplay | Game Over |
|:---:|:---:|:---:|:---:|
| ![Title](screenshots/start-screen.png) | ![Get Ready](screenshots/get-ready.png) | ![Gameplay](screenshots/gameplay.png) | ![Game Over](screenshots/game-over.png) |

### Mobile

<img src="screenshots/mobile-start.png" width="200" alt="Mobile Start"> &nbsp; <img src="screenshots/mobile-gameplay.png" width="200" alt="Mobile Gameplay">

</div>

## ✨ Features

- **Classic Flappy Bird visuals** — blue sky, green pipes with caps & shading, puffy clouds, city skyline
- **Cute illustrated bird** — yellow body, red beak, flapping wing, white tail
- **GET READY screen** — with tap hand icon, just like the original
- **Game Over panel** — score, best score, medals (bronze/silver/gold), NEW badge
- **Sound effects** — synthesized via Web Audio API (flap, score, hit, swoosh)
- **High score tracking** — persisted in localStorage
- **Mobile responsive** — tap to flap, portrait-optimized 288×512 canvas
- **Retro pixel font** — Press Start 2P
- **Mute toggle** — sound on/off
- **Zero dependencies** — single HTML file, no frameworks

## 🎮 Controls

| Platform | Action |
|----------|--------|
| Desktop | `Space` / `↑` / Click |
| Mobile | Tap anywhere |

## 🖼️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 Canvas | Game rendering |
| Vanilla JavaScript | Game logic & physics |
| Web Audio API | Synthesized sound effects |
| CSS3 | UI & scaling |

## 🏗️ Architecture

```
flappy-bird-game/
├── index.html              # Complete game (single file)
├── screenshots/            # Playwright-captured screenshots
└── README.md
```

## 🚀 Getting Started

```bash
git clone https://github.com/alfredang/flappy-bird-game.git
open index.html
```

No build step — single HTML file.

## 📝 License

MIT
