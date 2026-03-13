## Spotify Clone — Collaborative Web Project (Exam Colab MNN)

## Project Overview
This project is UI/UX prototype designed to replicate the aesthetic and navigation of Spotify. Our primary goal was to master complex frontend layouts using semantic HTML and advanced SCSS.

**⚠️ Important Note on Project Scope:** This repository represents a **visual UI/UX prototype**. 
**No Audio:** Functional music playback is not implemented.
***Work in Progress:** Due to exam time constraints, only the core navigational pages (Home, Search, library and Song View) were built. Other peripheral pages are not included in this build.


## 👥 Team Structure & Ownership
This application was developed by a two-person team. We divided the application into functional zones to manage our Git workflow efficiently and minimize merge conflicts.

## Team Contributions



**Nona Zabakhidze** | **Song Page, Search Page, Bottom Player Bar, and SCSS setup.** |

## My Individual Contribution
Here are the specific parts of the project I built:

### 1. Song Page (`song.html` & `_song-page.scss`)
* **Responsive Layout:** Built the layout for the song details, including the album cover and playback controls. It adapts from a mobile view to a larger desktop view.
* **No-JS Interactivity:** I used the "Checkbox Hack" (hidden checkboxes) to make the **Lyrics** and **Queue** sections open and close using only CSS.

### 2. Search Page (`search.html` & `_search-page.scss`)
* **Category Flex:** Created the flex layout for the "Browse All" search categories using Flexbox.
* **Sticky Mobile Header:** Made the top search bar sticky so it stays at the top of the screen when you scroll down on a mobile phone.

### 3. Music Player Bar (`_player.scss`)
* **Bottom Player:** Styled the fixed music player at the bottom of the screen, including the play buttons, volume bar, and song info.
* **Scrolling Text:** Wrote a custom `@keyframes` animation so that if a song title is too long, it slowly scrolls sideways (like a marquee).

### 4. SCSS Variables & Mixins
I helped set up and use the SCSS structure to make our styling easier:
* **Variables (`_variables.scss`):** Used variables for our dark theme colors (like `$primary-color: #060606`) and font sizes to keep the design consistent.
* **Mixins (`_mixins.scss`):** Created a few helpful mixins to avoid repeating code. For example, I made mixins for button hover effects and the layout of the search cards.

---

## How We Worked
* **Mobile First:** We styled everything for small mobile screens first, and then added desktop styles using `@media (min-width: 768px)`.
* **Git Branches:** I worked on separate branches (like `search`, `player` and `song-page`) to keep my code safe before merging it into the `main` branch. 

---
*Created for the frontend web development examination module.*
