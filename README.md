# CryptoGraphy 🔐

**CryptoGraphy** is an interactive, visually-rich web app that teaches classical and modern cryptography through animated, step-by-step visualizers. Each cipher gets its own dedicated page with a "tactical / sci-fi" UI (neon glassmorphism, animated backgrounds, monospace + Orbitron typography) so you can watch encryption and decryption happen in real time instead of just reading about it.

## ✨ Features

- **Interactive cipher visualizers** — enter your own plaintext/key and watch each algorithm transform it step by step.
- **Cipher evolution timeline** — a chronological walkthrough of how cryptography evolved from classical to modern ciphers.
- **Side-by-side comparison view** — compares ciphers across criteria like security, speed, and use case.
- **Animated, game-like UI** — built with Tailwind CSS, Three.js background effects, and GSAP animations for smooth transitions.
- **No build step required** — pure static HTML/CSS/JS pages that run directly in the browser.

## 🗂️ Pages

| Page | File | Description |
|---|---|---|
| Landing / Loader | `index.html` | Intro / initializing-protocols splash screen that redirects into the app |
| Home | `homepage.html` | Main hub linking to every cipher visualizer |
| Cipher Evolution Timeline | `evolution.html` | Visual timeline of cryptography's history |
| Cipher Comparison | `comparison.html` | Tactical side-by-side comparison of all ciphers |
| Caesar Cipher | `caeser.html` | Classic shift cipher visualizer |
| Modified Caesar Cipher | `modified.html` | Variant of the Caesar cipher |
| Vigenère Cipher | `Vigenere.html` | Polyalphabetic substitution cipher |
| Playfair Cipher | `Playfair2.html` | Digraph substitution cipher |
| Hill Cipher | `hill.html` | Matrix/linear-algebra based cipher |
| Rail Fence Cipher | `railfence.html` | Transposition cipher |
| Vernam Cipher (One-Time Pad) | `vernam.html` | XOR-based perfect-secrecy cipher |
| DES | `des.html` | Data Encryption Standard protocol visualizer |
| AES-128 | `aes.html` | Advanced Encryption Standard visualizer (uses CryptoJS) |

## 🛠️ Tech Stack

- **HTML5 / CSS3** — page structure and custom neon/glassmorphism styling
- **[Tailwind CSS](https://tailwindcss.com/)** (via CDN) — utility-first styling
- **[Three.js](https://threejs.org/)** (r128, via CDN) — animated 3D/particle backgrounds
- **[GSAP](https://gsap.com/)** — smooth UI animations (also available as an npm dependency)
- **[CryptoJS](https://cdnjs.com/libraries/crypto-js)** — used for AES encryption
- **Google Fonts** — Orbitron & JetBrains Mono
