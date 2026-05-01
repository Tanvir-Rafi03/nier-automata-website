# NieR:Automata — Fan Website

A cinematic, interactive fan tribute to NieR:Automata built entirely with vanilla HTML, CSS, and JavaScript.

**[Live Demo →](https://nier-automata-website.vercel.app)**

---

## Pages

### `nier-hero.html` — Main Landing Page
The centerpiece of the site. Features a scroll-scrubbed video hero where the game's footage plays frame-by-frame as you scroll down. Below the hero:
- Three.js WebGL canvas showcasing the YoRHa units
- Animated oscilloscope display
- Parallax ghost typography
- Looping cinematic footer video

### `index.html` — Hand Tracking Experience
An experimental interactive page that uses your webcam to detect hand position. The closer your hand gets to the camera, the further the animation progresses — a flipbook-style sequence rendered on a canvas in real time.

### `slider.html` — Character Gallery
A minimal slider showcasing the three main characters: **2B**, **9S**, and **A2**.

---

## Tech Stack

- **Three.js** — WebGL unit display canvas
- **GSAP / ScrollTrigger** — Scroll-linked animations
- **MediaPipe Hands** — Webcam hand tracking
- **Canvas API** — Flipbook frame rendering & oscilloscope
- **Vanilla JS / CSS** — No frameworks, no build step

---

## Run Locally

No build step required — just open the files in a browser.

```bash
git clone https://github.com/Tanvir-Rafi03/nier-automata-website.git
cd nier-automata-website
# open nier-hero.html in your browser
```

> The hand tracking page (`index.html`) requires camera access and works best in Chrome or Edge.

---

## Project Structure

```
├── nier-hero.html     # Main scroll-scrub landing page
├── index.html         # Hand tracking flipbook experience
├── slider.html        # Character gallery slider
├── style.css          # Global styles
├── nier.mp4           # Hero scroll-scrub video
├── footer.mp4         # Footer looping video
├── center.png         # Hero center graphic
├── 2B.jpg             # Character — 2B
├── 9S.jpg             # Character — 9S
├── A2.jpg             # Character — A2
└── slider_frames/     # Flipbook animation frames
```

---

*Glory to Mankind.*
