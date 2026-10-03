# Dr Project

A responsive static website for **Dr. M. Usman Sarwar Orthopedics**, built with HTML, Tailwind CSS (CDN), custom CSS, and vanilla JavaScript.

## Overview

This project contains a marketing/presence site with sections for:
- Hero and appointment CTA
- About doctor/profile
- Orthopedic treatments
- Clinic/facility showcase
- Contact and footer details

The UI includes responsive navigation, smooth scrolling, and a subtle animated water-ripple visual effect.

## Project Structure

- `dr-usman-orthopedics/index.html` – Main webpage
- `dr-usman-orthopedics/styles.css` – Custom styling and animations
- `dr-usman-orthopedics/script.js` – Interactive behavior (mobile menu, scroll effects, smooth scroll, ripple animation)
- `dr-usman-orthopedics/*.png` – Image and logo assets

## Run Locally

Because this is a static site, you can open it directly or serve it with a local web server.

### Option 1: Open directly
Open:
- `dr-usman-orthopedics/index.html`

### Option 2: Serve via local server (recommended)
From repository root:

```bash
cd /home/runner/work/Dr-Project/Dr-Project
python3 -m http.server 8000
```

Then visit:
- `http://localhost:8000/dr-usman-orthopedics/index.html`

## Customization

- Update textual content in `index.html`
- Adjust color/spacing/animations in `styles.css`
- Edit interaction behavior in `script.js`
- Replace images in `dr-usman-orthopedics/` while keeping filenames (or update references in HTML)

## Deployment

This site can be deployed on any static hosting platform (for example GitHub Pages, Netlify, or Vercel static hosting).
