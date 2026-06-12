<div align="center">

# ⚡ YELLOW MELLOW ⚡
**The "Anti-PPT" Flash Quiz Engine**

[![Vibecoded](https://img.shields.io/badge/Built_With-Vibecoding-FFD600?style=for-the-badge&logo=code&logoColor=black)]()
[![JavaScript](https://img.shields.io/badge/Vanilla-JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()
[![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge)]()

</div>

---

## 📖 The Origin Story: Killing the PowerPoint

It started with a completely standard, uninspiring request: *"Can you make a PPT for the upcoming English grammar quiz?"*

As the English Wing Chairman at Shamsul Huda Academy, I knew a standard, click-through slide deck was going to put the crowd to sleep. I didn't want an academic test; I wanted a **high-stakes, TV reality show vibe**. I wanted tension. I wanted ticking timers, blaring alarms, dramatic music drops, and explosive answer reveals. 

So, I threw the PowerPoint idea out the window. 

Instead of opening Microsoft Office, I opened my code editor. Armed with a clear vision of the exact aesthetic I wanted, I vibecoded this entire single-file web application in exactly **1 hour**. 

**The Result?**
When the event started and we cast this engine to the main screen, the entire audience was absolutely *on fire*. The energy in the room shifted instantly. The custom audio triggers, the GSAP screen shakes, and the intense timer completely transformed a standard college grammar quiz into a live game show broadcast. 

---

## ✨ How the "Reality Show Vibe" Works

This isn't just a visual tool; it's a fully integrated audio-visual experience designed to keep the audience on the edge of their seats.

* **The Tension Engine (Timers & Alarms):** A 30-second circular SVG timer that pulses. When the time runs out, a hidden YouTube iframe automatically blasts an [alarm sound](https://www.youtube.com/embed/6BvpEAGNGHg?si=XBkpDgAMftG47-Sj), locking the screen and triggering a red vignette effect.
* **The Presenter's God-Mode:** A hidden, floating control panel allows the host to seamlessly trigger "Correct Answer" flashes, playing a preloaded [success chime](https://files.catbox.moe/amcuzj.mp3) exactly when the crowd expects it. 
* **Dynamic Audio Routing:** 
  * A continuous, low-level [tension track](https://www.youtube.com/embed/VReGLwDPMpE?si=a8Q-kKHh5NuhVi3P) runs in the background.
  * Round completions trigger a specific [transition audio cue](https://files.catbox.moe/quw7ow.mp3).
  * The final winner reveal podium sequence drops a dedicated [hype track](https://files.catbox.moe/69t2p9.mp3) while the DOM explodes with GSAP confetti.

## 🛠️ The Tech Stack (Or Lack Thereof)

* **100% Vanilla:** One single `index.html` file. No React, no build steps, no local servers needed. Just double-click and run.
* **GSAP:** Powers the buttery-smooth elastic bounces, staggering table reveals, and particle physics (confetti/lightning).
* **HTML5 Canvas:** Renders a continuous retro pixel grid and drifting lightning bolts behind the UI.

## 🚀 Running the Show

1. Clone or download the repository.
2. Open `index.html` in Google Chrome.
3. Press `F` to enter Fullscreen mode.
4. Hook your laptop up to the venue's display and audio system.
5. Use `SPACEBAR` to control the entire flow seamlessly while holding the mic.

---
<div align="center">
  <i>Never settle for a PPT when you can build a spectacle.</i><br>
  Built by <b>Fadil Muhammed P.</b>
</div>
