# Portfolio — Ajay Chakravarthy G

Personal portfolio site for **Ajay Chakravarthy G**, Cloud | DevOps Engineer based in Chennai, India.

Recruiter-friendly single page built from the CV: at-a-glance facts, career history at Tagit
(Trainee → Associate → DevOps Engineer), measurable impact, grouped skills and a downloadable CV.

## Stack

Single static `index.html`. No build step, no dependencies, no framework.
Fonts (Manrope, Inter, JetBrains Mono) load from Google Fonts; everything else is inline.

- Light and dark themes via CSS custom properties, with a manual toggle persisted to `localStorage`
- Respects `prefers-color-scheme` and `prefers-reduced-motion`
- Responsive down to 320px

## Local preview

```bash
python3 -m http.server 8899
# http://localhost:8899
```

## Deploy

Pushes to `main` deploy automatically to GitHub Pages via `.github/workflows/deploy.yml`.

## Contact

- Email — ajay.chakravarthyg@gmail.com
- LinkedIn — https://www.linkedin.com/in/g-ajay-chakravarthy/
