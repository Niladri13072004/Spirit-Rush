# 🌌 SPIRIT RUSH (BHAG BHAG)

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![React](https://img.shields.io/badge/React-19.0-61DAFB?style=flat&logo=react)](https://react.dev)
[![Three.js](https://img.shields.io/badge/Three.js-r181-black?style=flat&logo=three.js)](https://threejs.org)
[![Zustand](https://img.shields.io/badge/Zustand-State-orange?style=flat)](https://github.com/pmndrs/zustand)
[![Vite](https://img.shields.io/badge/Vite-6.0-646CFF?style=flat&logo=vite)](https://vitejs.dev)

A stunning, fast-paced **3D Retro-Futuristic Cyber Runner** game built using **React**, **Three.js (React Three Fiber/Drei)**, and **Zustand**. Dodge spikes, blast through incoming alien missiles, collect neon letters to form **BHAGBHAG**, and visit the Cyber Shop to upgrade your system capabilities!

---

## ✨ Features

* 🎮 **Immersive 3D Graphics:** Designed with React Three Fiber, realistic light casting, retrowave grid patterns, and atmospheric post-processing.
* 🏃 **Dynamic Difficulty & Speed:** Speed increases linearly as you collect letters. Game lanes expand dynamically from 3 up to 9 lanes!
* 👾 **Alien Enemies:** Face hover aliens that lock onto you and fire neon plasma missiles.
* 🛒 **Cyber Shop:** Collect gems during your run to purchase upgrades:
  * **Double Jump:** Jump mid-air to clear taller obstacles.
  * **Immortality:** Active shield that makes you invincible for 5 seconds.
  * **Repair Kit:** Instantly restores hit points.
  * **Max Life Up:** Adds permanently to your maximum health pool.

---

## 🎮 How to Play

| Action | Control Key | Swipe (Mobile/Trackpad) | Description |
| :--- | :--- | :--- | :--- |
| **Move Left** | `← Arrow` / `A` | Swipe Left | Dodge obstacles to the left lane |
| **Move Right** | `→ Arrow` / `D` | Swipe Right | Dodge obstacles to the right lane |
| **Jump** | `↑ Arrow` / `W` / `Space` | Swipe Up | Jump over spikes and missiles |
| **Immortality** | `Space` / Tap | Double Tap | Activate invincibility shield (if bought) |

---

## 🛠️ Tech Stack

- **Core:** React 19, TypeScript
- **3D Render Engine:** `@react-three/fiber`, `@react-three/drei`, `three.js`
- **Post-Processing:** `@react-three/postprocessing`
- **State Management:** `Zustand`
- **Icons:** `lucide-react`
- **Bundler:** Vite

---

## 🚀 Running Locally

### Prerequisites
Make sure you have **Node.js** (v18 or higher recommended) installed.

### Setup Instructions

1. **Clone and Navigate:**
   ```bash
   git clone https://github.com/Niladri13072004/Spirit-Rush.git
   cd Spirit-Rush
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env.local` file in the root directory and add your Gemini API Key:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Launch Development Server:**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to **[http://localhost:3000](http://localhost:3000)**.

---

> Designed and Developed by **Niladri** 🚀
