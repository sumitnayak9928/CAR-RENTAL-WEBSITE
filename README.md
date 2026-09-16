# Wayfarer — Car Rental Website

A responsive, static car rental landing page built with plain HTML, CSS and JavaScript — no frameworks, no build step.

## Features
- Booking search widget with pickup/return date validation
- Animated hero car (SVG, drives in on load, spinning wheels, glowing headlights)
- Fleet grid rendered dynamically from a JS data array (`script.js`)
- Interactive price estimator with a 10%+ multi-day discount
- Scrolling "trusted brands" strip
- "40-point inspection" section
- Callback request form with phone number validation
- Fully responsive (mobile nav included)

## Tech stack
- HTML5
- CSS3 (custom properties, Grid/Flexbox, keyframe animations)
- Vanilla JavaScript (no dependencies)
- [Google Fonts](https://fonts.google.com/): Space Grotesk + Inter

## Project structure
```
.
├── index.html    # page structure/content
├── style.css     # all styling and animations
├── script.js     # fleet data, form logic, price estimator
└── README.md
```

## Running locally
No build tools needed.

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR-USERNAME/wayfarer-car-rental.git
   cd wayfarer-car-rental
   ```
2. Open `index.html` directly in a browser, **or** for live-reload while editing, use the
   [Live Server VS Code extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   and choose "Open with Live Server".

## Editing the fleet
Car data lives in the `FLEET` array at the top of `script.js` — add, remove or edit entries there; the grid re-renders automatically.

## Deploying
This is a static site, so it can be hosted for free on **GitHub Pages**:
1. Push the repo to GitHub (see below).
2. Go to the repo's **Settings → Pages**.
3. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save — GitHub gives you a live URL in a minute or two.

## License
Free to use and modify for personal or commercial projects.
