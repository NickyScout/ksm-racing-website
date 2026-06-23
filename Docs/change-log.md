# Change Log

A simple dated list of changes. Add a new entry every time the project is edited.

---

## 2026-06-23 (published to GitHub)
**What was changed:**
- Installed Git and GitHub CLI.
- Created a git repository, added a `.gitignore` file, and made the first commit.
- Published the project as a new **public** repository on GitHub:
  `https://github.com/NickyScout/ksm-racing-website` (branch `main`).

**Why it was changed:**
- To put the project online and back it up on GitHub so it can be shared and
  updated easily.

---

## 2026-06-23
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`
- `Codes/code 2/personal-site-option2.html`
- `Codes/code 2/personal-style-option2.css`

**What was changed:**
- Design 1 hero image set to `../Images/tyre-perspective.jpg`.
- Design 1 My Story image set to `../Images/child-kart.jpg`.
- Removed the captions (text) under all Design 1 gallery images.
- Reframed the `walking-away.jpg` gallery image with `object-fit: cover` and
  `object-position: center 30%` so it shows the body, not just the head.
- Fixed all Design 2 image paths from `../Images/...` to `../../Images/...` so the
  pictures load correctly (HTML images and CSS background images).

**Why it was changed:**
- To use the requested images in the right sections.
- To make the gallery cleaner (no captions) and the walking-away photo look better.
- Design 2 is two folders deep, so it needed `../../Images/` to find the root
  `Images` folder. Before this fix its pictures were not showing.

---

## 2026-06-23 (documentation)
**Files changed:**
- Created the `Docs` folder with: `README.md`, `project-overview.md`,
  `file-structure.md`, `design-decisions.md`, `image-guide.md`, `change-log.md`,
  `testing-notes.md`, `next-steps.md`.

**Why it was changed:**
- To add simple, beginner-friendly documentation for the project.
