# Emoji Charades — Movies 😍🥰⭐👍😊😉

A fast, family-friendly emoji movie guessing game you can run in any modern browser.  
Pick languages (English/Hindi/Kannada/Telugu/Malayalam/Tamil), choose the round size and timer, and let players guess the movie from emojis. Press **Space** to reveal, **Double-Space** (or **Next**) to move on. Includes subtle background music (2 styles), confetti celebration, a centered **HINT** bubble showing the movie’s language, and a clean neon/3D button aesthetic.

**Live demo (GitHub Pages):**  
[Play Emoji Charades](https://mandeepkoursardarni.github.io/Emoji-movies-charades/)

---

## ✨ Features

- **Multiple languages**: English, Hindi, Kannada, Telugu, Malayalam, Tamil  
- **Centered HINT bubble**: Shows the current movie’s **language**  
- **Rounds & timer**: 10/20/30/50 rounds; 10/12/15/20-second timer  
- **Unique order**: No repeats within a session  
- **Controls**:  
  - **Space** → Reveal answer  
  - **Double-Space** → Next puzzle  
  - Buttons: **Reveal**, **Next**, **Skip**, **Restart**  
- **Music (Web Audio)**: 2 styles — *Fun Beat* and *Playful Plucks*  
- **Celebration**: Confetti + soft chime on reveal  
- **Aesthetics**: Neon 3D bottom buttons, glassmorphism, responsive layout  
- **Projector/mobile ready**: Scales nicely from phones to big screens  
- **Local persistence**: Saves selected categories, round size, and timer in `localStorage`  

---

## 📦 Tech Stack

- **HTML/CSS/JS** only (vanilla)  
- **Web Audio API** for music/SFX  
- **Canvas** for confetti & edge lights  
- **No external build/deps** — drop-in static file  

---

## 🚀 Quick Start

1. Clone or download this repo.  
2. Open `index.html` in Chrome/Edge/Firefox/Safari.  
3. The **Categories & Rounds** dialog opens automatically:  
   - Choose languages, round size, and timer.  
   - Click **Apply & Start**.  
4. Use **Space** to reveal, **Double-Space** (or **Next**) to proceed.  

> Tip: If audio doesn’t start automatically, click anywhere once (browser gesture unlocks audio).  

---

## 🎮 Controls & UI

- **Space** → Reveal the movie title  
- **Double-Space** → Next puzzle  
- **Reveal/Next/Skip/Restart** → Bottom neon buttons  
- **Music On/Off** + **Style** toggle → Top controls  
- **Shuffle** → Rebuild current session (keeps your settings)  
- **HINT** → Center top bubble showing the **language** for the current emoji puzzle  
- **Counter & Timer** → Same-size bubbles for visual balance  

---

## ⚙️ Configuration

All data lives inside `index.html`:

```js
{ t: "Movie Title", e: "🎬🍿✨", c: "Hindi movie" }


Enjoy! 🎬✨


