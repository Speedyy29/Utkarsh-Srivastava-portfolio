# Utkarsh Srivastava — Portfolio

Welcome to the portfolio website for Utkarsh Srivastava. This is a lightweight, responsive static site built with plain HTML, CSS and JavaScript showcasing projects, experience and a contact form.

🎯 Live (will be deployed via GitHub Pages):

https://Speedyy29.github.io/Utkarsh-Srivastava-portfolio/

---

## Preview

Open `index.html` to see the main portfolio layout (hero, experience, skills, projects and contact form).

## Local development

Quick steps to run locally (Windows PowerShell):

```powershell
cd 'C:\Users\HomePC\Desktop\Project\Portfolio'
# Start a simple HTTP server (Python 3)
python -m http.server 8000
# Then open http://localhost:8000/portfolio.html in your browser
```

Alternatively open `portfolio.html` directly in the browser for casual preview (some features like fetch-based contact form require serving over HTTP).

## What I added

- Responsive layout with glassmorphism styling
- Contact form wired to FormSubmit.co for quick email delivery (AJAX)
- Smooth interactions and small UI animations in `script.js`

## Deployment

This repository includes a GitHub Actions workflow that publishes the repository root to GitHub Pages whenever `main` is pushed. The action uses the `peaceiris/actions-gh-pages` action and `GITHUB_TOKEN` so no extra secret is required.

If the Pages site doesn't appear immediately, check the Actions tab in GitHub and the Pages settings for deployment logs.

## Changes & Notes

- If you want the contact form to use a different service (EmailJS, Netlify Forms, or your own backend) I can wire that instead.
- To use a custom domain, add a `CNAME` file to the repository root and configure your DNS.

## License

This repo contains personal portfolio code. Use it as a reference.

---

If you'd like any copy/visual polish, or to add a CI-based preview URL, tell me what to include and I will update the repo.
