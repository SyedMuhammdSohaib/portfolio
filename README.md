# Syed Muhammad Sohaib — Portfolio

Personal portfolio of **Syed Muhammad Sohaib**, Python Developer & AI Engineer from Lahore.

A simple, dark, single-page site in plain HTML and CSS with no build step and no animations.

## Run locally

Open `index.html` in a browser, or:

```bash
python -m http.server 8000
```

then visit http://localhost:8000

## Edit content

Open `index.html` and edit the section you want. The text for each section is plain HTML there.

- Screenshots go in `images/` (e.g. `resume-1.png`, `jarvis-1.png`)
- Demo videos go in `videos/`, or use a YouTube link

## Deploy

Hosted on Vercel as a static site. Every push to `main` redeploys automatically.

## Optional files

Drop these next to `index.html` and they show up automatically:

- `cv.pdf` adds a "Download CV" button
- `photo.jpg` replaces the initials in the round avatar
- `images/resume-1.png`, `images/clinic-1.png`, `images/jarvis-1.png`, `images/rag-1.png` add a screenshot to each project

## Contact form

Without setup, the form opens the visitor's email app. To receive messages directly, create a free form at formspree.io and paste its endpoint into `FORM_ENDPOINT` at the top of the script in `index.html`.
