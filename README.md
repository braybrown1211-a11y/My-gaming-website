# 🎮 Kyobi Games Web Portal
### *From Canva Design to a Functional GitHub Website*

## 📝 Project Overview
This project demonstrates the transition of a visual design created in **Canva** into a live, hosted web application on **GitHub Pages**. By using AI-assisted coding, I converted static design elements into a multi-page site featuring a playable, pure JavaScript game.

---

## 🚀 How to Reproduce This Project

### 1. Design & Asset Extraction
* **Design:** Create the website layout in Canva.
* **Export:** Download the design as high-quality `.png` files.
* **Assets:** The following files were used:
    * `Introduction.png`
    * `About The Company.png`
    * `Meet The Team.png`
    * `Prices.png`
    * `Disclamer.png`

### 2. GitHub Repository Setup
* Create a new public repository on GitHub.
* Upload all `.png` assets directly to the **main (root)** folder.
* **Note:** Filenames must match the code exactly (e.g., `Prices.png` is different from `prices.png`).

### 3. Creating the Homepage (`index.html`)
* Create a file named `index.html`.
* Use **HTML5** to structure the page sections (Hero, About, Team, Prices).
* Use **CSS3** within `<style>` tags to implement the "Kyobi" brand identity:
    * **Background:** `#02021a` (Dark Space Blue)
    * **Accents:** `#ff007f` (Cyber Pink)
* Implement **Hyperlinks** (`<a href="...">`) to connect the homepage to the game sub-page.

### 4. Game Development (`snake.html`)
* Create a second file named `snake.html`.
* **Engine:** Pure JavaScript using the HTML5 `<canvas>` element.
* **Logic:**
    * **Movement:** Event listeners capture arrow key inputs.
    * **Collision Detection:** JavaScript checks if the snake head coordinates match the food or the walls.
    * **Rendering:** A `setInterval` function redraws the game state every 100 milliseconds.

### 5. Deployment via GitHub Pages
* Navigate to **Settings > Pages** in the repository.
* Set the Source to the `main` branch.
* **The "Build" Process:** GitHub automatically triggers an "Action" to compile the site. Once the green checkmark appears in the **Actions** tab, the site is live.

---

## 🤖 The Power of AI in This Project
This documentation and the underlying code were generated and debugged using **AI collaboration**. 
* **Code Conversion:** AI interpreted the visual layout of the Canva images to write matching CSS.
* **Debugging:** AI identified "pathing" errors (like spaces in filenames) that prevented images from loading.
* **Logic Generation:** The Snake game was written in pure JavaScript without the need for external libraries.

## 🛠️ Vocabulary for the Class
* **Repository:** Your project's digital folder on GitHub.
* **Commit:** Saving your changes to the project history.
* **Deployment:** The process of taking code and making it a live website.
* **Pathing:** The "address" the code uses to find an image or another file (e.g., `./snake.html`).

---
**Built by [Braylon Broqn] with assistance from Gemini AI.**
