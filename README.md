# VeraceData Website

Static multi-page website for VeraceData, hosted via GitHub Pages.

## File Structure

```
veracedata/
├── index.html          # Home page
├── how-it-works.html   # How It Works page
├── why-it-matters.html # Why It Matters page
├── contact.html        # Contact / Book a Call page
├── css/
│   └── styles.css      # Shared stylesheet
└── README.md
```

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save** — your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Local Development

No build step required. Open any `.html` file directly in a browser, or use a simple local server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
