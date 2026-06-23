# Testing Notes

How to check that the website works. Go through this list after making changes.

## How to test with Live Server
1. Open the page file in VS Code (for example `Codes/personal-site.html`).
2. Right-click and choose **"Open with Live Server"**.
3. The page opens in your browser and refreshes when you save.

## Check that images load
- Look at the hero photo, the My Story photo, the gallery and the background images.
- No image should be broken (no empty box or broken-image icon).
- If an image is missing, check the path:
  - Design 1 uses `../Images/...`
  - Design 2 uses `../../Images/...`
- Also check the filename is spelled exactly right (same capital/small letters).

## Check the navigation links
- Click each link in the top menu (About / Story, Driver, Tracks, Gallery,
  Sponsors).
- Each link should scroll to the correct section on the same page.
- Click the Instagram and TikTok links and make sure they open the right pages in a
  new tab.

## Check the layout on different screen sizes
- Make the browser window narrow and wide.
- On a wide screen, sections should show side by side in columns.
- On a narrow screen (phone size), sections should stack into one column and stay
  readable.
- You can also use the browser's device/responsive view to test phone sizes.

## Issues found and whether they were fixed
- **2026-06-23 – Design 2 images not showing.** Cause: paths used `../Images/` but
  the files are two folders up. **Fixed** by changing to `../../Images/`.
- **2026-06-23 – walking-away gallery image showed only the head and looked
  squeezed.** **Fixed** with a taller box plus `object-fit: cover` and
  `object-position: center 30%`.
