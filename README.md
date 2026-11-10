# People’s Feelings

A lightweight, interactive English lesson for Grade 3, built with plain HTML, CSS and JavaScript.

**Live lesson:** https://syetori.github.io/peoples-feelings/

- Exactly 10 widescreen lesson screens.
- Eight separate, click-to-play English pronunciations.
- Team quiz: 15 questions, teacher-controlled scoring and completed-question marks.
- Six separately revealed emotion pictures.
- Nine scrambled sentences with shared team scores.
- Three reflection choices with persistent vote counters.
- Homework: **WB ex 1 p22**.

Use the arrow keys, the on-screen arrows, or click an empty left/right part of the slide. Choose your local video on screen 2. Video files stay on your computer and need to be selected again after a reload. Scores and votes are stored in the current browser; they do not sync across devices.

## Performance

The complete deployable website is approximately 453 KB, down from 6.45 MB (93% smaller). The first screen requires about 71 KB before HTTP compression. WebP images, AAC speech audio, minified scripts/styles, reusable audio objects and idle-time image preloading keep the lesson lightweight. No frameworks, remote fonts, analytics or external runtime dependencies are used. Save-Data and slow connections skip full-deck preloading.

## Running locally

Open `index.html` directly, or serve this directory using any static web server. The site works under a GitHub Pages repository path because all asset URLs are relative.

Design and lesson material were supplied for this classroom presentation.
