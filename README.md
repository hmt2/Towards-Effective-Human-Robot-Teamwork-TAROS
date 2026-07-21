# Towards Effective Human-Robot Teamwork — TAROS Workshop

Website for the TAROS workshop **"Towards Effective Human&ndash;Robot Teamwork"**,
organised by Hazel Taylor, Marie Farrell, and Yasmeen Rafiq (University of Manchester).

## Structure

- `index.html` — the single-page site (overview, call for posters, speakers, schedule, participants, organisers)
- `css/styles.css` — styling
- `js/script.js` — mobile nav toggle

## Running locally

No build step needed. Either open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying to GitHub Pages

1. Push this repo to GitHub (already done if you're reading this on GitHub).
2. In the repo settings, go to **Pages**.
3. Set the source to the branch containing this site (e.g. `main`) and the root folder `/`.
4. The site will be published at `https://<org>.github.io/<repo>/`.

## TODOs before launch

Search the site for `TODO` / highlighted text to find items still needing real content:

- Confirmed workshop date, time, and venue (currently marked TBC)
- Poster submission format, deadline, and submission link/email
- A contact email for enquiries
- Final keynote speaker (once confirmed) and any additional invited speaker bios
