# The Promise, Scotland

A static site exploring Scotland's commitment to children, young people and families in care, with three audience-specific pages off a shared landing page.

## Pages

- `index.html` — landing page, picks an audience
- `promise-quest.html` — for ages 7–11, a playful map journey
- `the-promise-teens.html` — for ages 12–18, "Have Your Say"
- `keeping-the-promise-staff.html` — for staff & practitioners, a reflective practice module that generates a personal pledge PDF

## Stack

Plain HTML / CSS / JS, no build step. The staff page uses jsPDF (loaded from CDN) to generate the downloadable Pledge.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Designed for Netlify. Either drag-and-drop the folder onto Netlify Drop, or connect this repo to Netlify with default settings (no build command, publish directory = repo root).

