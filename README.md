# KHATRON KE KHILADI — Event Website

Official event website for **KHATRON KE KHILADI**  
BBA Semester V • EventTech & Quality Management  
K.L.E. Society’s Lingaraj College, Belagavi

**Date:** 7 November 2026  
**Venue:** PG Building – Specialization Classroom

## Live Features

- Mobile-friendly single-page site
- Home, About, Challenges, Rules, Event Details, Registration, Contact
- Direct link to Google Forms registration
- Responsive design (desktop + mobile)

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) → New Project → Import the repo.
3. Framework Preset: **Other** (static).
4. Root Directory: leave as `/` (or set if the site is in a subfolder).
5. Deploy. Vercel will serve `index.html` automatically.

## Deploy to GitHub Pages

1. Push to GitHub.
2. Repo Settings → Pages → Source: Deploy from a branch → `main` / root.
3. Site will be available at `https://<username>.github.io/<repo-name>/`

## Local Preview

Open `index.html` in a browser, or run a simple static server:

```bash
npx serve .
# or
python -m http.server 3000
```

## Project Structure

```
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── README.md
```

## Notes

- Registration form: Google Forms (link in the Register section).
- No build step required — pure HTML/CSS/JS.
- Colour palette: Black, Red, Yellow, White (as per event branding).
