# ☀️ SpaceWhizz – Stellar Stories

SpaceWhizz is an educational web app designed for kids to learn about **space weather** through storytelling, videos, and interactive quizzes.  
Built for NASA Space Apps Challenge 2025 under the *Stellar Stories* category.

---

## 📖 Overview

SpaceWhizz transforms the invisible science of **solar flares, geomagnetic storms, and auroras** into kid-friendly adventures.  
Children progress through **9 story-driven adventures**, each with 3 short missions.  
After each mission, they complete a fun quiz to unlock the next level.  
SpaceWhizz is built like a storybook adventure. Kids begin with Meet the Sun ☀️ — a friendly guide to the star at the center of our solar system. From there, they unlock a journey of nine adventures, each containing three short missions.
Every adventure is themed around a real-world impact of space weather. In Dance of Lights 🌌, kids discover the beauty of auroras. In The Lost Tractor 🚜, they learn how GPS signals affect farmers. In The Silent Sky ✈️, they explore why pilots sometimes lose communication. Later, in The Blackout City ⚡️, they see how solar storms can even knock out electricity.
After each animated video, kids solve a short quiz challenge. Passing the quiz unlocks the next mission — making learning feel like play, while reinforcing key concepts. As they progress, they collect badges, building a sense of achievement.
And here’s the exciting part: our Sun-Watch feature connects directly to **NASA’s CCMC DONKI API**. This means children don’t just learn about solar flares in theory — they see real flare events from the last 30 days, presented in kid-friendly cards with simple icons and animations. It’s like watching the Sun tell its story in real time.
SpaceWhizz blends storytelling, play, and NASA data into one seamless experience — transforming space weather from abstract science into a living adventure that children can explore step by step.”

Key Features:

- 🎬 Short animated videos powered by `next-video` and **Mux streaming**  
- 🌀 Smooth storytelling animations with **Motion** (`motion.div`)  
- 📡 Real-time solar flare feed via NASA **CCMC DONKI API** (Sun-Watch feature)  
- 🏅 Gamification with badges, progression, and unlockable adventures  

Demo: 👉 [SpaceWhiz](https://space-whiz.vercel.app)

---

## ❓ Problem Statement – *Stellar Stories*

Space weather is powerful but **invisible and often forgotten**.  
Kids rarely know how solar storms affect:

- 🚜 Farmers who depend on GPS  
- ✈️ Pilots who rely on communication signals  
- 🧑‍🚀 Astronauts exposed to radiation  
- ⚡ Entire cities dependent on power grids  

When children don’t see or understand these forces, they miss both the **wonder** and the **importance** of space weather.  
The *Stellar Stories* challenge calls for creative ways to make this science **engaging, visible, and meaningful**.

---

## 🎥 Demo & Link

- Live Demo: [SpaceWhiz](https://space-whiz.vercel.app)  
- Video Demo: [Video](https://www.youtube.com/watch?v=7WWSCfQajis)

---

## 🎯 Target Users

- 👦 **Children (ages 8–14)** → primary learners  
- 👩‍🏫 **Teachers** → fun classroom tool to explain abstract science  
- 👨‍👩‍👧 **Parents** → meaningful screen time for kids  
- 🌍 **General Public** → anyone curious about space weather  

---

## 💡 Solution Overview

SpaceWhizz answers the challenge with:

- **Storytelling:** Adventures like *Dance of Lights* (auroras) and *The Blackout City* (power grid failures)  
- **Interactive Quizzes:** Kids solve challenges to unlock new missions  
- **NASA Data:** Live solar flare feed via **CCMC DONKI API** presented in kid-friendly cards  
- **Gamification:** Badges, achievements, and progressive unlocks to keep curiosity alive  

---

## 🏗️ Architecture Overview

**Tech Stack:**

- [Next.js 15](https://nextjs.org/) → core framework  
- [Motion](https://motion.dev/) → animations  
- [next-video](https://github.com/pacocoursey/next-video) + [Mux](https://mux.com/) → video player + streaming  
- [NASA CCMC DONKI API](https://kauai.ccmc.gsfc.nasa.gov/DONKI/) → solar flare data (Sun-Watch feature)  

**High-Level Flow:**
User → Next.js UI (React + Motion)
→ Video lessons (next-video + Mux)
→ Quiz Engine (custom React state)
→ Sun-Watch feed (NASA CCMC DONKI API)
→ Progress & Badges stored client-side

---

## ⚙️ Installation

Clone and run the project locally:

```bash
# 1. Clone repo
git clone https://github.com/<your-username>/spacewhizz.git
cd spacewhizz

# 2. Install dependencies
yarn install

# 3. Setup environment variables
# .env.local
MUX_TOKEN_ID=your_mux_token_id
MUX_TOKEN_SECRET=your_mux_token_secret
NASA_API_BASE=https://kauai.ccmc.gsfc.nasa.gov/DONKI/WS

# 4. Run development server
yarn dev
```

---

## 🚀 Future Plans

Expand with more adventures & challenges

Add interactive videos

Integrate more NASA datasets (auroras, CMEs, asteroids)

## Our Team

- KH Anabil Ditisha 
  email: <ditisha03@gmail.com>

- Arpon Sarkar Choity 
  email: <arponsarkar2024@gmail.com>

- Shahriar Imrose Soscho 
  email: <shahriarimrosesoscho@gmail.com>

- Md Masrur Rahman 
  email: <masrur.mmrs@gmail.com>
