# CosmicExplosions 2026

**A Cambridge Extragalactic Transients Workshop**
27–31 July 2026 | Kavli Institute for Cosmology Cambridge (KICC)

Live site: https://cambridgetransients.github.io/CosmicExplosions2026/

---

## Site Structure

```
CosmicExplosions2026/
├── index.html          # Home / Overview
├── programme.html      # Draft programme
├── participants.html   # Registered participants
├── logistics.html      # Travel, venue, accommodation
├── css/
│   └── style.css       # Shared stylesheet
├── _config.yml         # GitHub Pages config
└── README.md
```

## Deploying to GitHub Pages

1. **Create the repository** on GitHub under the `cambridgetransients` organisation:
   - Repo name: `CosmicExplosions2026`
   - Visibility: Public

2. **Push this directory** as the repository contents:
   ```bash
   cd /path/to/CosmicExplosions2026
   git init
   git add .
   git commit -m "Initial site build"
   git remote add origin https://github.com/cambridgetransients/CosmicExplosions2026.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages** in the repository settings:
   - Go to **Settings → Pages**
   - Under *Source*, select **Deploy from a branch**
   - Choose `main` branch, `/ (root)` folder
   - Click **Save**

4. The site will be live at:
   `https://cambridgetransients.github.io/CosmicExplosions2026/`
   within a minute or two of the first push.

## Making Updates

All pages are plain HTML files — edit directly. The shared stylesheet is `css/style.css`.

No build step is required. GitHub Pages serves the files as-is.

Key things to update as the workshop approaches:
- `programme.html` — finalise talk titles, confirm TBC speakers, adjust timings
- `participants.html` — add confirmed local Cambridge participants, update TBC statuses
- `logistics.html` — add workshop dinner venue once confirmed

## Local Preview

Open any HTML file directly in a browser, or use a simple local server:

```bash
# Python 3
python3 -m http.server 8000
# then open http://localhost:8000
```

## Contact

Organiser: Nikhil Sarin — nsarin.astro@gmail.com
