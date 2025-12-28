# 🌌 Vizzl Quiz: Galactic Laser Run Engine

**A high-retention 3D quiz visualization engine built for the [Vizzl Quiz YouTube Channel](https://www.youtube.com/@VizzlQuiz).**

## 📖 About
This project is a custom-built web application designed to generate engaging, automated video content for social media (YouTube Shorts/TikTok). It combines a retro-wave aesthetic with logic puzzles to maximize viewer retention.

Instead of standard static slides, this engine renders a real-time 3D "warp tunnel" experience using **Three.js**, simulating a cockpit view where the player travels through space while solving IQ questions.

## ✨ Key Features
* **3D Environment:** Infinite procedural warp tunnel with neon laser obstacles and floating asteroids.
* **Cinematic Mode:** Automated "Intro" and "Outro" sequences designed specifically for screen recording (OBS/Camtasia).
* **Dynamic Camera:** The camera physically banks and shakes based on movement and "collisions," creating an immersive feel.
* **Quiz Logic:** Built-in engine handling 25 questions, timers, score tracking, and "Did You Know?" fact reveals.
* **Visual FX:** Bloom effects, neon lighting, and dynamic UI elements that react to game states.

## 🚀 How to Use (For Recording)
1.  **Launch:** Open `index.html` in a modern browser (Chrome/Edge recommended for performance).
2.  **Cinematic Intro:** The engine automatically starts with a "Welcome" sequence. Start your screen recording here.
3.  **The Quiz:** The game cycles through 25 logic/IQ questions.
    * *Timer:* 20 seconds per question.
    * *Reveal:* Highlights the correct answer and updates the streak.
    * *Fact:* Displays a fun fact after every question.
    * *Breaks:* Includes "Mid-roll" breaks at questions 5, 10, 15, and 20 to encourage subscribing.
4.  **Outro:** Ends with a call-to-action sequence.

## 🛠️ Tech Stack
* **Core:** HTML5, CSS3, Modern JavaScript (ES6 Modules)
* **3D Engine:** [Three.js](https://threejs.org/) (via CDN)
* **Styling:** Google Fonts (Orbitron/Montserrat) & FontAwesome
* **Assets:** Procedural generation (no external 3D models required)

## 📝 Customization
To change the questions, edit the `puzzles` array inside `index.html`. The structure supports:
* Question Text (`q`)
* 4 Options with Emojis (`options`)
* Correct Answer Index (`correct`)
* Fun Fact (`fact`)

---
*© 2025 Danish Khan | Vizzl Quiz*
