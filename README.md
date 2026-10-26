# Northstar — CFA Economics PWA starter

A responsive, offline-first study companion with eight original Economics lessons, three practice questions per lesson, local progress tracking, and installable PWA scaffolding.

## Run locally
Service workers require localhost or HTTPS. From this folder, run:
- `python3 -m http.server 8000`
- Open `http://localhost:8000`

## Install / deploy
Deploy the folder to any static host that serves HTTPS (for example, GitHub Pages or Netlify). Open the URL in a supported browser and use its install/add-to-home-screen action.

## Current features
- Eight Economics modules aligned to the 2026 CFA Level I module titles
- Original explanations and practice questions (not copied from CFA curriculum)
- Progress and quiz scores saved in browser localStorage
- Offline caching via service worker after first successful load
- Responsive desktop/mobile layout

## Important notes
- This is a prototype, not an official CFA Institute product.
- It does not include official CFA questions or reproduce proprietary curriculum text.
- The lesson text is a concise first draft. To make each session reliably 15–20 minutes, the next iteration should add worked examples, diagrams, retrieval practice, spaced repetition, and a larger question bank.
- Progress is stored on the current browser/device only; it does not sync between devices.
