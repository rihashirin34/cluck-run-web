# 🎤 Cluck & Run

A modern voice-controlled runner game built using HTML5 Canvas and Web Audio API.

Make noise. Jump. Survive.

---

## 🚀 Live Demo
(Add your GitHub Pages link here after deployment)

---

## 🎮 How It Works

- The character runs automatically.
- Obstacles spawn from the right.
- Microphone detects sound.
- Loud sound = Jump.
- The longer you survive, the faster it gets.

---

## 🧠 Features

- 🎤 Real-time microphone input
- 📈 Dynamic difficulty scaling
- 💥 Collision detection
- 🏆 High score saved in localStorage
- 📱 Responsive design
- 🎨 Clean modern UI
- ⚡ Smooth animation using requestAnimationFrame

---

## 🛠 Tech Stack

- HTML5 Canvas
- Vanilla JavaScript
- CSS3
- Web Audio API

---

## 🔊 How Microphone Works

The game uses:

- getUserMedia()
- AudioContext
- AnalyserNode
- RMS (Root Mean Square) volume detection

Volume is smoothed to avoid sudden spikes.

---

## 📦 Installation

Clone the repository:

