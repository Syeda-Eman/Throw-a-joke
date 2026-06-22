# Throw a joke!

A vibrant, arcade-style single-page web application that throws random jokes at the click of a button. This project was built as part of an HTML/CSS/JS crash course to master DOM text manipulation and randomized arrays without relying on visual asset bloat (like emojis or images).

---

## 🚀 Features

* **Retro Arcade Aesthetic:** A bold, high-contrast `#ffeb3b` yellow background paired with clean, black-and-white layout containers.
* **Pixel-Style Button Architecture:** Uses the classic `Courier New` monospace font and a hard 3D block-shadow effect to mimic retro 8-bit video game buttons.
* **Tactile Press Animation:** Utilizing CSS transforms to give the button a physical "sinking" effect when clicked.
* **True Randomization Engine:** Powered by JavaScript's math utilities to pull a completely random joke from a data pool every single time.

---

## 🛠️ Technologies Used

* **HTML5:** Clean structural layout utilizing semantic semantic tags (`<body>`, `<button>`, `<div>`).
* **CSS3:** * **Monospace Typography:** Using `Courier New` to achieve a clean, blocky "pixel text" look.
    * **Pseudo-classes (`:active`):** Leveraging `transform: translate()` to animate real-time button physics on click.
* **JavaScript (ES6):**
    * **Arrays:** Storing a scalable list of text-only strings.
    * **Math Utilities:** Combining `Math.random()` and `Math.floor()` to dynamically generate valid array index numbers.
    * **DOM Manipulation:** Utilizing `document.getElementById().innerText` to instantly swap out text nodes on the fly.

---

## 📂 Code Logic Breakdown

The JavaScript engine relies on two main parts:
1. **The `list` Array:** A simple collection of text strings containing the jokes. Adding a new joke is as easy as adding a new string inside the brackets.
2. **The `throwJoke()` Function:** * It calculates a random number between `0` and the total number of jokes in the list.
   * It finds the HTML text box by its ID (`box`).
   * It replaces the old text with the new random joke.

---

## 📦 How to Run

1. Copy the code into a file named `index.html`.
2. Double-click the file to launch it instantly in any web browser.
3. Smash that **"throw a joke"** button!
