# Image Guide

## Required image filenames
These images must exist in the `Images` folder (do not rename them):

- `helmet-profile.jpg`
- `standing.jpg`
- `tyre-perspective.jpg`
- `driving.jpg`
- `child-kart.jpg`
- `number-one.jpg`
- `walking-away.jpg`

The folder may also contain extra photos (for example `focused-kart.jpg`,
`on-track.jpg`, `on-track2.jpg`) that can be used later.

## Where the images must be stored
All images live in the **root `Images` folder**:
```
personal website/Images/
```
Keep every photo here so the whole project shares one image folder.

## Why the paths use ../Images/
The HTML and CSS files are inside the `Codes` folder, not in the root. The `../`
part means **"go up one folder"**. So from `Codes/personal-site.html`:

- `../Images/driving.jpg` means: go up to the project root, then into `Images`.

### Important: Design 2 uses ../../Images/
Design 2 is **two folders deep** (`Codes/code 2/`). To reach the root `Images`
folder it must go up **twice**, so it uses `../../Images/` instead of `../Images/`.

- Design 1 (`Codes/...`) → `../Images/...`
- Design 2 (`Codes/code 2/...`) → `../../Images/...`

If the wrong number of `../` is used, the pictures will not show.

## Image cropping notes (object-fit and object-position)
- **`object-fit: cover`** makes an image fill its box without stretching. The parts
  that do not fit are cropped (cut off). This keeps photos from looking squashed.
- **`object-position`** controls which part of the photo stays visible when it is
  cropped. For example `object-position: center 30%` keeps the upper-middle part.
- The `walking-away.jpg` gallery image was a tall, phone-style photo. It is given a
  taller box and `object-position: center 30%` so it shows the body, not just the
  head, and does not look squeezed.

## Which images are used where (Design 1)
- **Hero / Intro photo:** `tyre-perspective.jpg`
- **My Story section:** `child-kart.jpg`
- **Hero background:** `driving.jpg`
- **Sponsors background:** `walking-away.jpg`
- **Gallery:** `tyre-perspective.jpg`, `number-one.jpg`, `driving.jpg`,
  `helmet-profile.jpg`, `child-kart.jpg`, `walking-away.jpg`

## Which images are used where (Design 2)
- **Hero photo:** `helmet-profile.jpg`
- **Hero background:** `walking-away.jpg`
- **My Story section:** `child-kart.jpg`
- **Sponsors background:** `driving.jpg`
- **Gallery:** `tyre-perspective.jpg`, `number-one.jpg`, `driving.jpg`,
  `walking-away.jpg`, `standing.jpg`
