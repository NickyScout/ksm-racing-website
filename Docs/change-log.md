# Change Log

A simple dated list of changes. Add a new entry every time the project is edited.

---

## 2026-06-23 (new gallery photos)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Added two new photos to the Racing Moments gallery: `on-track.jpg` and
  `on-track2.jpg`.
- Removed the tyre-perspective photo (`tyre-perspective.jpg`) from the gallery.

**Why it was changed:**
- New on-track photos were added to the `Images` folder and requested for the
  gallery; the tyre-perspective photo was no longer wanted there.

---

## 2026-06-23 (gallery re-framed and rearranged)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Rearranged the Racing Moments gallery into equal, portrait-shaped cards
  (no more large/wide mosaic tiles).
- Each card now uses a 4:5 aspect ratio with `object-fit: cover`, so vertical
  photos fill the card nicely without big empty borders and without heavy cropping.
- The grid is responsive (`auto-fit`), so cards reflow on smaller screens.

**Why it was changed:**
- `contain` made the photos look too zoomed out; this format frames the photos
  better and keeps the layout tidy.

---

## 2026-06-23 (gallery shows full photos)
**Files changed:**
- `Codes/personal-style.css`

**What was changed:**
- Changed the gallery images from `object-fit: cover` to `object-fit: contain`
  so each photo shows fully instead of being heavily cropped.
- The card background fills the empty space around each photo.

**Why it was changed:**
- The reframed photos were cropping too much and only showed half of the driver.

---

## 2026-06-23 (gallery cleanup)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Removed the child karting photo (`child-kart.jpg`) from the Racing Moments gallery.
- Removed the "on track" photo (`driving.jpg`) from the gallery.
- Reframed the remaining gallery photos with `object-position: top` (class
  `photo-top`) so heads are no longer cropped off.

**Why it was changed:**
- To keep only the preferred photos and make sure faces/heads show properly.

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
