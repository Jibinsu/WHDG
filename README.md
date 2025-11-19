# 🎲 40k Command Bunker: The Chosen Edition

A tournament-grade, single-page web application designed to give **Death Guard** players an unfair advantage in battlefield clarity. This tool eliminates cognitive load, tracks game state, and ensures you never forget a rule, stratagem, or aura range again.



> *"Forged in the heat of battle to solve a simple problem: remembering all your rules."*

## ⚡ New in v2.0 (Tournament Ready)

The app has been overhauled with features specifically requested for competitive play:

* **🚨 State Persistence:** Close the app, refresh the page, or let your battery die—your wound counts, CP, VP, and current phase are saved instantly to your device's memory. You never lose game data.
* **💡 No-Sleep Mode:** Uses the browser's `Wake Lock API` to prevent your screen from dimming or locking during a game.
* **🧠 Context-Aware Stratagems:** A dynamic bar that automatically displays **only** the Stratagems usable in the current phase (with full rules text).
* **⚠️ Math-Checking:** Automatically warns you when a unit falls Below Half-Strength (Battleshock risk) or when a model with *Deadly Demise* is destroyed.
* **🌗 Dark Mode:** Instantly toggle between high-contrast Light Mode and battery-saving Dark Mode.

## 🌟 Core Features

* **Tactical Task Forces:** Units are grouped into logical battlefield roles (e.g., "Executioner Block," "Artillery Spotter") rather than just a list of names.
* **Synergy Reminders:** Yellow "Tactics Cards" explain *exactly* how your character buffs interact with their bodyguards (e.g., how *Vector of Disease* math works on T12 targets).
* **Game Phase Tracker 🕒:** Tracks whose turn it is and what phase it is.
* **Dynamic Aura Ranges:** The top bar automatically updates your **Contagion Range** (3", 6", or 9") based on the current Turn number.
* **Command Console:** A sticky footer to track Command Points (CP) and Victory Points (VP), with auto-incrementing CP in Command Phases.
* **Multi-Model Wound Counter ❤️‍🩹:** Track wounds for complex multi-model units (like Terminators) individually.

## 🚀 Installation (iPad / Mobile)

This app is designed to behave like a **native iOS/Android app**.

1.  **Host or Open:** Open the `index.html` file in Safari (iOS) or Chrome (Android).
2.  **Add to Home Screen:** Tap the "Share" button and select "Add to Home Screen."
3.  **Launch:** Open the icon from your home screen. It will launch in **Full Screen Mode** (no address bar, no browser buttons) for a totally immersive experience.

## 🛠️ Technology Stack

Built with pure, bulletproof web technologies. No frameworks, no build steps, no lag.

* **HTML5** (Offline capable)
* **CSS3** (Modern Variables, Flexbox, Dark Mode support)
* **Vanilla JavaScript** (ES6, LocalStorage API, Wake Lock API)

## 🎮 How to Use

1.  **Start Game:** Click the button in the top right. The app initializes Turn 1 and sets your Contagion Range to 3".
2.  **Select a Unit:** Tap a unit group on the left (e.g., "Executioner Block").
3.  **Track Wounds:** Use the `-` and `+` buttons. If a model dies, the text turns red. If the unit is below half-strength, a warning appears.
4.  **Check Stratagems:** Look at the bar above the console. It shows exactly what you can spend CP on *right now*.
5.  **Next Phase:** Click "Next Phase" to advance the game state. The app automatically handles CP generation.

## ⚖️ Disclaimer

This is a personal project and a coding exercise. All Warhammer 40,000 unit names, stats, abilities, and Stratagems are the intellectual property of **Games Workshop**. This tool is intended for personal use by individuals who own the official codexes. **Please support the official products.**
