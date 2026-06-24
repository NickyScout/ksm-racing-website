# Change Log

A simple dated list of changes. Add a new entry every time the project is edited.

---

## 2026-06-24 (About Me tone matched to the rest of the site)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Rewrote the About Me paragraphs with fuller, flowing sentences so the language and
  tone match the other sections (Driver Profile, Tracks, Goals). Kept simple words.

**Why it was changed:**
- The sentences had become too short and did not match the rest of the website.

---

## 2026-06-24 (About Me: simple words, formal style)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Reworded About Me to use simple, everyday words but keep a formal style (no slang,
  no contractions). The quote was simplified to "My goal is to get a little faster
  every time I race."

**Why it was changed:**
- The previous version used overly fancy words; the goal is simple wording with a
  formal tone.

---

## 2026-06-24 (About Me made formal)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Reworded the whole About Me section (lead, quote, all four mini-blocks and the
  five timeline steps) in a more formal tone.

**Why it was changed:**
- Requested a more formal style throughout the section.

---

## 2026-06-24 (About Me tone balanced)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Adjusted the About Me wording so it is natural but not too informal, especially
  the "Off the track" part. Kept it genuine and professional for teams and sponsors.

**Why it was changed:**
- The previous rewrite was too casual.

---

## 2026-06-24 (About Me wording made more natural)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Reworded the About Me / My Story text (lead line, quote, the four mini-blocks and
  two timeline steps) to sound more natural and less polished/AI-like.
- Same facts and meaning, just a more genuine, everyday voice.

**Why it was changed:**
- Some phrasing sounded too AI / a bit cringe.

---

## 2026-06-24 (stats moved back)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Reverted the stats band. The stats (31.8s, 4+, Top 5) are back in their original
  place near the bottom of the Tracks section.

**Why it was changed:**
- The stats band under the hero was not wanted.

---

## 2026-06-24 (stats moved to the top)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Moved the key stats (31.8s best lap, 4+ endurance events, Top 5 finishes) out of
  the bottom of the Tracks section and into a bold "stats band" right under the hero.
- The stats are now one of the first things visitors and sponsors see.

**Why it was changed:**
- The stats were easy to scroll past where they were before.

---

## 2026-06-24 (My Story made more engaging)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Rewrote the My Story section to be more engaging: a strong opening line, a
  pull quote, and short mini-blocks with subheadings (How it started, The turning
  point, Off the track, What racing has taught me).
- Added "fact chips" (age, academy, endurance, main track).
- Added a "My journey so far" timeline with five steps.
- All facts kept the same as before; only the wording and layout changed.

**Why it was changed:**
- The section read like a flat list and was not engaging to read.

---

## 2026-06-23 (restored on-track2 photo)
**Files changed:**
- `Codes/personal-site.html`
- Moved `on-track2.jpg` from the project root into the `Images` folder.

**What was changed:**
- Put the `on-track2.jpg` photo back into the Racing Moments gallery.
- The file was in the wrong place (project root), so it was moved into `Images`
  so the gallery path works.

**Why it was changed:**
- Requested to put the on-track photo back.

**Note:** `on-track.jpg` (without the "2") is still missing from the project, so it
was not restored. Add that file to `Images` if you want it back too.

---

## 2026-06-23 (removed on-track photos)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Removed the two on-track photos (`on-track.jpg`, `on-track2.jpg`) from the
  Racing Moments gallery. Their image files were no longer in the Images folder,
  so they were showing as broken.

**Why it was changed:**
- Requested removal; also fixes the broken image links.

---

## 2026-06-23 (removed sponsor logo placeholders)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Removed the "Supported by" logo placeholder strip from the Sponsors section.

**Why it was changed:**
- It was not wanted after seeing it.

---

## 2026-06-23 (sponsor logo placeholders)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Added a "Supported by" strip in the Sponsors section with five placeholder
  logo slots that say "Your logo here".

**Why it was changed:**
- To show sponsors there is ready-made space for their logo on the website.

---

## 2026-06-23 (sponsors section wording)
**Files changed:**
- `Codes/personal-site.html`

**What was changed:**
- Updated the Sponsors ("Open to opportunities") section so it no longer says
  contact is only through social media. It now points to the contact form, email
  and social media.
- Added a "Get in touch" button that jumps to the Contact section.

**Why it was changed:**
- A contact form and email were added, so the wording needed to match.

---

## 2026-06-23 (thank-you message after sending)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- After the contact form is sent, the form is hidden and a "Thank you!" message
  appears on the same page (no page reload).
- The form now submits through the FormSubmit AJAX endpoint so the thank-you can
  show instantly. If JavaScript is off, the normal form still works as a fallback.

**Why it was changed:**
- To confirm to the visitor that their message was sent successfully.

---

## 2026-06-23 (contact form and email)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Added a new **Contact** section with a working contact form (Name, Email,
  Message) and an "Email me" button.
- The form is powered by FormSubmit.co and sends messages to
  `miliaevak@outlook.com` (no backend needed).
- Added a "Contact" link to the top navigation.

**Why it was changed:**
- To let teams and sponsors contact the driver directly from the website.

**Note:** FormSubmit sends a one-time activation email the first time the form is
used. The owner must click the link in that email once to start receiving messages.

---

## 2026-06-23 (gallery sideways scroll)
**Files changed:**
- `Codes/personal-site.html`
- `Codes/personal-style.css`

**What was changed:**
- Turned the Racing Moments gallery into a sideways (horizontal) scroller so the
  photos slide left and right instead of stacking below each other.
- Added left and right red arrow buttons that scroll the gallery.
- Added a small script (`scrollGallery`) so the arrows scroll the row smoothly.

**Why it was changed:**
- Requested: the walking photo (and the others) should scroll sideways with an
  arrow instead of stacking.

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
