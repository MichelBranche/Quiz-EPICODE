# EPICODE Benchmark Quiz (Build Week) – TEAM4

Single-page web app that reproduces the EPICODE “Benchmark Exam” experience: Welcome screen, timed multiple-choice quiz, and final results.  
Built as a team project during Build Week, with a focus on clean UI, responsive layout, and a smooth quiz flow.

## Preview
- **Mockups included** in `/mockup` (welcome + quiz screen).
- (Optional) **Live demo**: _add your GitHub Pages link here_

---

## Features
- **Single-page flow** (no page reloads): Welcome → Quiz → Results
- **Timed questions** with visual timer ring
- **Multiple choice** questions (one answer only)
- **Randomized answers** per question
- **Score tracking** and final results screen
- **Responsive UI** (desktop + mobile)

---

## Tech Stack
- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**
- Optional helper: **progressbar.js** (for the circular timer ring)

---

## Project Structure
```text
TEAM4-Quiz-Test/
├── assets/                # Images (background, logo, icons)
├── css/                   # Stylesheets
│   └── welcome.css        # Main styles (welcome + quiz UI)
├── js/                    # (if present) scripts / libs
├── mockup/                # Reference screens from the exam
├── index.html             # Single-page app entry
└── script.js              # Quiz logic (render, timer, score, results)
