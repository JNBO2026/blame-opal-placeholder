# Blame Opal — Placeholder Game

A retro pixel-shooter placeholder site for [Blame Opal Studio](https://blameopal.studio).

While the studio site is being built, visitors can shoot the falling **BLAME OPAL** word out of the sky, collect stackable power-ups, and chase the level-100 win screen.

## Run locally

```bash
npm install
npm start
```

Then open [http://localhost:3000](http://localhost:3000).

## How to play

- **Move:** ◄ ► / A / D / drag finger or mouse
- **Fire:** SPACE / click / tap & hold
- Destroy every white pixel of "BLAME OPAL" before any of them reach the red ground line.
- Catch power-ups dropped by destroyed pixels:
  - **R** Rapid fire
  - **S** Spread shot (3 bullets in a fan)
  - **E** Explosive (slower, blast radius)
  - **F** Freeze (pauses the descent for 5 seconds)
  - **N** Nuke — **1-in-100 rare**, instantly clears the screen
- Power-ups **stack**. Collect Rapid + Spread + Explode and you'll fire rapid explosive spreads.
- 100 levels total, each noticeably faster than the last.

## Tech

- Pure HTML5 Canvas game (no external game engine)
- Express static-file server (Node ≥ 18)
- Roboto Mono (body) + custom WetInk Display (headline) fonts
- Fully responsive — playable on desktop, tablet, and mobile

## Project structure

```
.
├── public/
│   ├── index.html         # game + UI
│   └── fonts/             # WetInk Display
├── server.js              # Express static server
├── package.json
└── README.md
```

## Connect

- Instagram: [@blameopal](https://www.instagram.com/blameopal)
- TikTok: [@blameopal](https://www.tiktok.com/@blameopal)
- LinkedIn: [Blame Opal](https://www.linkedin.com/company/blame-opal/)
- Email: [james@blameopal.studio](mailto:james@blameopal.studio)

## License

MIT
