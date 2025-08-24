# Date Everything! Realizer

## Overview

This project is a **self-contained, offline web app** that helps track which characters in *Date Everything!* can be “Realized” based on your **S.P.E.C.S.**

If you are unfamiliar with the game, [here's a short explanation](https://www.youtube.com/watch?v=GhM-G3lI_Yo). As someone who's never played a dating sim before this one, it's honestly a delight.

---

## Features

* **Character classification**

  * **Eligible Now** → You meet all 5 requirements.
  * **Nearly There** → You’re not eligible yet, but all shortfalls ≤ 5.
  * **Realized** → Characters you’ve marked as realized (they won’t appear in the other lists).
* **Stat entry** — Input your Smarts, Poise, Empathy, Charm, and Sass (0–100).
* **Progress saving** — Uses browser `localStorage` to remember your stats and realized list between sessions.
* **Toggle Realized** — Mark/unmark characters with a single button.

---

## Usage

1. Download the HTML file.
2. Open it in any modern browser (Chrome, Firefox, Edge).
3. Enter your S.P.E.C.S. values.
4. Click **Check** to classify characters.
5. Use the **Realize/Unrealize** buttons to manage your realized list.
6. Use **Reset** to clear all saved progress.

---

## Safety

* It’s a static HTML file — no executables, no hidden processes.
* Works offline, makes **no external requests**.
* If in doubt, you can open the HTML in any text editor to review all code.

---

## Credits

* **Created by**: u/Shackleface
* **Tools Used**: ChatGPT 5 for coding assistance
* **Source data**: [Character images, background image](https://dateeverything.wiki.gg/wiki/Characters), [character S.P.E.C.S. prerequisites](https://www.screenhype.co.uk/date-everything-realization-guide/)
* **Inspiration**: My love for *Date Everything!* and making the process of Realizing characters easier. Also ADHD, if we're being real.
