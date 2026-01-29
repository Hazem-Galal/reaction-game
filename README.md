# Reaction Timer ⏱️

A clean, modern **Reaction Timer** game built with **vanilla JavaScript** and **Three.js**, designed as a polished portfolio project that demonstrates precise timing logic, state management, and immersive in-context UI design.

The game focuses on clarity, responsiveness, and user experience — keeping all interaction, guidance, and feedback inside the play area for a distraction-free experience.

---

## 🎯 Purpose

This project was built as a **frontend portfolio piece** to showcase:

- Accurate millisecond-level timing
- Robust state management
- Clean, maintainable vanilla JavaScript
- Thoughtful UX and visual hierarchy
- Interactive graphics using Three.js
- Desktop and mobile accessibility

---

## 🕹️ How It Works

1. Start the game by clicking **Start**, clicking the play area, or pressing **Space** (desktop).
2. Wait for the shape to turn **green**.
3. React as quickly as possible by clicking/tapping the play area.
4. Your reaction time is measured and displayed instantly.
5. Clicking too early counts as a **false start**.

All instructions and feedback appear **inside the game area** to maintain focus and immersion.

---

## 🚀 Features

- **Accurate reaction timing** using `performance.now()`
- **Randomized stimulus delay** (1–5 seconds)
- **False start detection** with immediate feedback
- **Session statistics**
  - Last reaction time
  - Average reaction time
  - Best reaction time
  - Total attempts (rounds started)
- **Human-friendly performance grading**
  - Amazing (<150ms)
  - Very Good (150–200ms)
  - Good (200–250ms)
  - Average (250–300ms)
  - Below Average (>300ms)
- **Keyboard & mouse support (desktop)**
- **Touch-optimized UX (mobile)**
- **In-context overlays** for instructions and results
- **Clean, modern visual design**
- **No frameworks, no storage APIs, no dependencies beyond Three.js**

---

## 🎨 Design & UX Principles

- All guidance and feedback live **inside the play area**
- Instructions appear **once** and dismiss smoothly when play begins
- Minimal UI outside the game to keep focus on interaction
- Responsive layout optimized for desktop and mobile
- Clear visual states (idle, waiting, active, error, result)

---

## 🧠 Technical Highlights

- Vanilla JavaScript (no frameworks)
- Explicit game state machine
- Proper cleanup of timers and animation flags
- Three.js scene with:
  - Camera
  - Lighting
  - Animated geometry
- Performance-safe animation loop
- Accessible keyboard handling without double-trigger bugs

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Three.js**

---

## 📱 Responsive & Accessible

- Works on desktop, tablet, and mobile
- Touch-first behavior on mobile (no keyboard hints)
- Keyboard support on desktop
- High contrast color palette for readability

---

## 📦 Installation & Usage

No build steps required.



👤 Author
Built by Hazem Ali as a frontend portfolio project.

If you’re reviewing this as a recruiter or engineer:
this project intentionally avoids frameworks to highlight core JavaScript, timing precision, and UX thinking.
