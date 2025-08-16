# 🥁 Drum Kit — HTML, CSS & JavaScript

A simple, responsive, and fun drum kit you can play with your keyboard or mouse. Click the on-screen pads or press the keys **W A S D J K L** to trigger different drum sounds. 
---

## ✨ Features

- **Interactive buttons** with visual press animation. 
- **Keyboard support** for quick jamming: `w a s d j k l`. 
- **Custom graphics** for each drum pad via background images. 
- **Lightweight** — no frameworks, just vanilla HTML/CSS/JS. 

---

## 🧩 Tech Stack

- **HTML5** for structure (pads, title, footer).
- **CSS3** for layout, typography, and pressed-state animation. 
- **JavaScript (ES5+)** for event handling (click + keydown) and audio playback. 

---

**Notes:**
- `index.html` defines seven buttons (`.drum`) labeled **w, a, s, d, j, k, l** and loads the stylesheet & script.  
- `styles.css` sets the theme, assigns background images to each key class (`.w`, `.a`, …), and styles the `.pressed` animation state.  
- `index.js` attaches event listeners for clicks & keyboard, plays the corresponding sound, and toggles the pressed animation class. 

---

## 🕹️ How to Play

1. **Open** `index.html` in any modern browser. 
2. **Click** on any pad **or** press keys on your keyboard:  
   - **w** → tom-1  
   - **a** → tom-2  
   - **s** → tom-3  
   - **d** → tom-4  
   - **j** → snare  
   - **k** → crash  
   - **l** → kick-bass  
   Sounds are loaded from `/sounds/*.mp3`.
3. Watch the pad **flash** with a pressed effect when triggered.

---

## 📁 Project Structure

```markdown
drum-kit/
├─ index.html         # Main HTML file with drum buttons and layout
├─ styles.css         # CSS for styling drum pads, animations, and theme
├─ index.js           # JavaScript for sound playback and interactions
├─ sounds/            # Drum sound effects (mp3 format)
│  ├─ tom-1.mp3
│  ├─ tom-2.mp3
│  ├─ tom-3.mp3
│  ├─ tom-4.mp3
│  ├─ snare.mp3
│  ├─ crash.mp3
│  └─ kick-bass.mp3
├─ images/            # Drum pad background images
│  ├─ tom1.png
│  ├─ tom2.png
│  ├─ tom3.png
│  ├─ tom4.png
│  ├─ kick.png
│  ├─ crash.png
│  └─ snare.png
└─ README.md          # Documentation
