# God's Honour (GH) Portfolio

Portfolio site for God's Honour (GH). Tech solutions. Digital innovation.

Services shown on the site:

- Phone Repairs
- Web Design
- App Design
- IT Solutions

## Files

```
index.html                  The whole site (HTML and CSS, no build step)
assets/phone-repairs.jpg    Service photos
assets/web-design.jpg
assets/app-design.jpg
assets/it-solutions.jpg
assets/favicon.svg          Browser tab icon
assets/logo-mark-light.svg  GH mark for dark backgrounds
assets/logo-mark-dark.svg   GH mark for light backgrounds
.nojekyll                   Tells GitHub Pages to serve the files as they are
```

## Run it locally

Open `index.html` in a browser. There is nothing to install.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `gh-portfolio`.
2. Upload these files, or push them from this folder:

   ```
   git init
   git add .
   git commit -m "Add GH portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/gh-portfolio.git
   git push -u origin main
   ```

3. In the repository, open Settings, then Pages. Under Build and deployment, choose Deploy from a branch, pick `main` and the `/ (root)` folder, and save.
4. After a minute the site is live at `https://<your-username>.github.io/gh-portfolio/`.

## Editing

- Change text, services and colours directly in `index.html`. The colours are defined once at the top of the `<style>` block.
- Replace the photos in `assets/` with your own, keeping the same file names.
- Add your phone, email and location in the closing section when you are ready.
