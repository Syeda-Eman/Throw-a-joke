# 🫧 Virtual Bubble Wrap Speedrun

An addictive, satisfying mini-game built to practice advanced frontend skills. This project features a responsive grid layout, high-precision time tracking, and browser-synthesized audio effects.

---

## 🚀 Features

* **Satisfying Pop Visuals:** Shiny, 3D-looking bubbles that flatten out into an "unclickable" popped state when clicked.
* **Live Audio Synthesis:** Generates a clean, realistic plastic popping sound on-the-fly using the Web Audio API (no external `.mp3` files needed).
* **Speedrun Stopwatch:** A millisecond-precise timer that triggers on your very first pop and locks your score the moment the last bubble bursts.
* **Victory Celebration:** An animated congratulations banner that appears only when the entire board is clear.
* **Insta-Reset:** A "Fresh Sheet" controller that safely purges the board, wipes the clock, and sets up a brand new game state.

---

## 🛠️ Technologies Used

* **HTML5:** Basic UI shell and structural containers.
* **CSS3:** * **CSS Grid:** Matrix alignment (`grid-template-columns: repeat(6, 1fr)`) for perfect spacing.
    * **Radial Gradients:** Mimics realistic lighting reflections to give the bubbles a 3D bubble effect.
    * **Keyframe Animations:** Powering the bouncing victory banner effect.
* **JavaScript (ES6):**
    * **Web Audio API:** Manipulating oscillators (`sine` wave) and exponential ramps to generate procedural sound effects.
    * **High-Precision Timing:** Calculating elapsed time via `Date.now()` differences rather than rough intervals.
    * **State Gates:** Using Boolean flags to manage when the game is actively tracking time.

---

## 📂 File Structure Explained (Human-Friendly Code)

The codebase utilizes clean, simple, human-centric naming conventions:

* **`setup()`**: Clears the container, resets all global states (counters, timers), and injects fresh interactive bubble nodes onto the screen.
* **`tick()`**: Calculates the exact millisecond differences and updates the display text dynamically.
* **`makeSound()`**: Spins up a momentary audio context to play a custom sound signature that rapidly drops in pitch and volume.

---

## 📦 Getting Started

1. Save the code into a file named `index.html`.
2. Open `index.html` in any web browser.
3. Start popping and try to beat your high score!
