# Personal Website

A simple academic personal website for Abraham George.

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deploy to GitHub Pages

1. Create a new GitHub repository named `Abraham190137.github.io` (replace with your GitHub username if different).

2. Push this folder to the repository:

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin git@github.com:Abraham190137/Abraham190137.github.io.git
git push -u origin main
```

3. In the repository on GitHub, go to **Settings → Pages** and set the source to deploy from the `main` branch (root `/`).

4. After a minute or two, the site will be live at `https://Abraham190137.github.io`.

### Alternative: project site

If you prefer a repository named something else (e.g. `website`), push to that repo and enable GitHub Pages from the `main` branch. The site will be available at `https://Abraham190137.github.io/website/`.

## Updating content

- **Bio / affiliation**: edit the About section in `index.html`.
- **Publications**: add entries under the appropriate year in `index.html`.
- **CV**: replace `assets/resume.pdf` with an updated PDF.
- **Photo**: replace `assets/profile.jpg`.
