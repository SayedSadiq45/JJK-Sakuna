# JJK Sakuna

An atmospheric **Jujutsu Kaisen-inspired Domain Expansion scroll experience** created by **Sayed Sadiq**.

Scroll through a cinematic sequence of motion, generated lightning, hand signs, and a final domain reveal. The experience is designed as a single focused visual journey with no framework or build step required.

## Live Website

**[Open JJK Sakuna](https://jjk-sakuna-sayed-sadiq.vercel.app/)**

## Highlights

- Full-screen cinematic hero with looping video
- Scroll-driven scene progression
- Canvas-generated lightning with glow, flicker, and ambient strikes
- Layered hand-sign sequence with parallax movement
- Responsive layout for desktop and mobile screens
- Reduced-motion support for accessibility
- Runs directly in the browser with plain HTML, CSS, and JavaScript

## Run Locally

Keep the project files together and open `index.html` in a browser.

For the smoothest local experience, serve the folder with any static file server, for example:

```bash
npx serve .
```

## Project Assets

Keep these filenames unchanged when replacing visual assets:

| File | Purpose |
| --- | --- |
| `hero.mp4` | Looping hero background video |
| `1.png` | Left hand reaching right |
| `2.png` | Right hand reaching left |
| `3.png` | Formed hand sign |
| `4.png` | Character reveal |
| `5.png` | Temple or domain background |
| `6.png` | Domain Expansion title artwork |

Lightning is generated in code, so no additional lightning image is required. The hero kanji text can be edited directly in `index.html` by searching for `kanjiRail` and `kanjiCorner`.

## Author

Built and maintained by **[Sayed Sadiq](https://github.com/SayedSadiq45)**.

## License

This project is available under the [MIT License](LICENSE).