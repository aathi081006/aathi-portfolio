# Aathi Narayanan KV — Portfolio

Personal portfolio site for Aathi Narayanan K V, Full Stack &amp; Software Development (Fresher). Built as a single self-contained `index.html` — no build step, no dependencies.

## Run locally

Just open `index.html` in your browser. Or, with VS Code:

1. Open this folder in VS Code.
2. Install the **Live Server** extension (if you don't have it).
3. Right-click `index.html` → **Open with Live Server**.

## Deploy on GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Structure

```
.
├── index.html      # entire site — HTML, CSS, and JS in one file, photo embedded as base64
└── README.md
```

## Editing

- **Contact links**: search for `mailto:`, `wa.me`, `github.com/aathi081006`, and `linkedin.com/in/aathinarayanan70` in `index.html` to update.
- **Photo**: the profile photo is embedded directly as a base64 data URI inside the `<img id="profile-img">` tag in the hero section — replace that string to swap photos, or extract it to a separate file if you'd rather keep the HTML lighter.
- **Content**: resume-derived sections (About, Skills, Experience, Projects, Education) are plain HTML blocks — edit text directly.
