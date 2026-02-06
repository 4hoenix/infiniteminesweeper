# 🚩 Infinite Minesweeper

**Infinite Minesweeper** is a procedural, never-ending twist on the classic puzzle game. Unlike traditional versions, this world generates as you explore, allowing you to travel millions of tiles in any direction. Every coordinate is unique, and your progress is saved automatically.

## 🚀 Key Features
* **Infinite Exploration:** The world is mathematically generated. You will never hit a wall or run out of mines to find.
* **Persistent World:** Your revealed tiles, flags, camera position, and custom settings are saved to your browser's local storage automatically.
* **Lifetime Stats:** Tracks your total tiles revealed and your cumulative playtime (Days, Hours, Minutes, Seconds).
* **Warp System:** Use the **GO** button to jump to any coordinate (e.g., `500, -500`).
* **Theming:** Toggle between Light and Dark modes and choose a custom **Accent Color**.

## 📊 Understanding the HUD
In the top-left corner, you will see two counters next to the minimap:
* **F (Flags):** This shows the total number of flags you currently have placed in the world.
* **D (Detonations):** This shows how many mines you have accidentally clicked. Since the world is infinite, the game continues even after hitting a mine, marking it with a red background.

## 🕹️ How to Run the Game
You do not need an internet connection to play. To launch the game:
1. **Locate the file:** Find your `index.html` file in your folders.
2. **Open with Browser:** Right-click the file and select **Open With**, then choose any web browser (Chrome, Edge, Firefox, or Safari).
3. **Play:** The game will load instantly. To return to your game later, simply open the same file again.

## 🎮 Controls
* **Left Click / Primary Tap:** * Click a **Hidden Tile** to reveal it.
    * Click a **Numbered Tile** to "Chord" (instantly clear all surrounding tiles if the correct number of flags are placed).
* **Right Click / Secondary Tap:** Place or remove a flag.
* **Click & Drag:** Pan the camera around the world.
* **Scroll Wheel / Two-Finger Slide:** Zoom in and out.
* **WASD / Arrow Keys:** Use the keyboard to move the camera.
* **Enter Key:** Quickly trigger the "Jump" button when in the Warp menu.

## 🛠️ Gameplay Tips
1. **Chording:** If you see a "3" and have placed 3 flags around it, click the "3" to automatically open the other surrounding squares.
2. **Warping:** The **GO** button acts as a toggle. Opening the Warp menu will automatically close the Settings menu to keep the UI clean.
3. **Resetting:** To start completely over, use "Regenerate World" in the menu. This will wipe your save and create a brand new world seed.

---
*Created with focus on infinite procedural generation and browser-based persistence.*
