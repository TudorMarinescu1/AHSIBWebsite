# Agoura High School IB Website

Static website for the Agoura High School IB Program.

## Run Locally

Open `website/index.html` directly in a browser, or serve the website folder locally:

```powershell
python -m http.server 8000 --bind 127.0.0.1 --directory website
```

Then visit:

```text
http://127.0.0.1:8000/
```

## What's Included

- Modernized home page with program overview, value proposition, contact details, and key planning facts.
- Separate pages for diploma requirements, course groups, HL/SL balance, core requirements, and assessment expectations.
- AHS IB course catalog with summaries adapted from public AHS IB materials.
- Interactive 11th-12th grade schedule builder with drag and drop, automatic two-year HL placement, AP/CP custom courses, sample plan, reset, print, saved local state, and diploma checks.

## Page Files

All website code and assets live in the `website` folder. Each page has its own folder with an `index.html` file and a matching page stylesheet. Shared styles live in `website/styles.css`; page-specific rules live beside their HTML. `website/index.html` sends visitors to `website/home/index.html`.

## Publishing

This site is made of plain static files, so it can be published with GitHub Pages or any static host without a build step.
