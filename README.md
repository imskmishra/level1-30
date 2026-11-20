# IBD L1–L30 Master Prompt Tool · भक्ति • सिनेमा • दिव्यता

A single-page tool for Indian Bhakti Dhara (IBD) that builds ready-to-use master prompts for devotional posters and videos.

## Features
- Platform rules: YouTube Video, Shorts, Instagram Reels, Post, Portrait, Story (ratio, resolution, title TOP, bottom clean)
- 18 deities, couples, Dashavatar, Shiv Parivar and Ram Darbar with nature control
- 30 quality levels (L1–L30) with camera, lighting, VFX and face settings that scale by tier
- Voiceover in Hindi, English or Hinglish, video length, colour LUT, storyboard, audio, export notes
- **Devotee Mode:** you in aarti or prayer, with an identity lock so the face is kept unchanged
  - up to 5 saved photos, each labelled (Me, Father, Mother and so on)
  - One photo at a time, Couple (e.g. Father + Mother), or Same person with many photos
- Copy prompt, download as .txt, save prompt packs in the browser
- Hindi and English artistic fonts (Cinzel Decorative, Yatra One, Tiro Devanagari Hindi, Manrope)

## Important
This tool writes **prompts only**. It does not generate images. For Devotee Mode, attach the same photos in an image tool that accepts reference photos. Results can still drift from the photo, so regenerate if the face changes.

## Run locally
Open `index.html` in a browser. No build step or server needed.

## Deploy on GitHub Pages
1. Create a new repository and upload all files in this folder.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. Your site appears at `https://<your-username>.github.io/<repo-name>/` after a minute or two.

## Privacy
Photos, labels, selections and saved packs are stored only in your browser (localStorage). Nothing is uploaded. Photos are resized to 700 px on the longest side. Use **Remove all** on shared computers. Data does not move between browsers or devices.

## Files
- `index.html` — the whole app (HTML, CSS, JavaScript)
- `.nojekyll` — tells GitHub Pages to serve files as they are
- `LICENSE` — all rights reserved by default; change if needed

## Fonts
Loaded from Google Fonts. If offline, the page falls back to system fonts.
