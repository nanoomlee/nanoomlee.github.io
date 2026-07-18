# Your Personal Website

Plain HTML/CSS, no build step. 3 pages: `index.html` (about), `projects.html` (research), `publications.html`, all sharing `style.css`. The "CV" nav link points directly to a `cv.pdf` file rather than a separate page.

## Edit content
Open each `.html` file and replace bracketed placeholders like `[Field]`, `Your Name`, research/publication descriptions, etc. Add a real photo by replacing the `.headshot` div in `index.html` with `<img src="photo.jpg" alt="Your Name">`.

## CV PDF
`cv.pdf` is already in this folder and the "CV" link in the nav bar points to it directly. Replace it with an updated export whenever your CV changes (keep the filename `cv.pdf`).

## Preview locally
Just double-click `index.html` to open it in a browser, or run:
```
python3 -m http.server 8000
```
then visit `http://localhost:8000`.

## Deploy for free
**GitHub Pages** (easiest): create a repo, push these files, enable Pages in repo Settings → Pages → source = main branch. Your site will be live at `https://your-username.github.io/repo-name`.

**Netlify/Vercel**: drag-and-drop this folder onto netlify.com/drop for an instant live URL, or connect a GitHub repo for auto-deploys.

**Custom domain**: buy one (Namecheap, Google Domains, etc.) and point it at your GitHub Pages/Netlify site via their DNS instructions.
