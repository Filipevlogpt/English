# English with Filipe — Complete V6.8 Repository

This repository contains the complete V6.8 package extracted from the supplied project ZIP.

## Main website files
- `web/index.html` — website UI
- `app.js` — application JavaScript
- `script0.js`, `script1.js`, `script2.js`, `test.js` — project JavaScript files
- `web/explanations.json` — explanations content
- `web/vocab.json` — vocabulary database/content
- `web/trilingual.json` — EN/PT/RO language data
- `web/quizzes.json` — quiz/test data

## Media/resources
- `web/assets/filipe-story.jpeg` — website story image
- `slides/` — 30 PNG teaching slides (A1–C1)
- `web/audio/` — included MP3 pronunciation audio resources

## Backend/data
- `start_server.py` — Python HTTP server/backend
- `english_with_filipe.db` — SQLite database

## Deployment note
GitHub can store all of these files. GitHub Pages can serve the static website files, but it cannot execute the Python server or SQLite backend. For the complete interactive backend, use a Python-capable hosting service and keep the `web/` directory as the frontend/static assets.

The original project documentation and maintenance scripts are preserved in this repository.
