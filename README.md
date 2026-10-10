# Bjorn Stephany: Portfolio

A one-page portfolio with a cream notebook look. Plain HTML and CSS, no build step.

## Files

- `index.html`: page content
- `style.css`: all styling (colors are variables at the top of the file)
- `CV_HEADSHOT_LINEN.jpeg`: your headshot. Not included; add it yourself (see below)

## Run it locally

Open `index.html` in a browser. Keep all files in the same folder.

## Add your headshot

Put `CV_HEADSHOT_LINEN.jpeg` in the same folder as `index.html`. It appears at the top right. Until then, a dashed "headshot" placeholder shows. A portrait crop (about 3:4) works best.

## Fill in the project placeholders

In `index.html`, find the `Projects` section. Each project has:

1. A title, tech stack, date, and one-line description.
2. An image box: `<a class="shot" href="#">`. Replace `#` with the repo or website URL.
   To show a screenshot, replace the link text with `<img src="your-image.png" alt="Project name">` and add this to `style.css`:

   `.shot img{width:100%;height:100%;object-fit:cover}`

The two entries marked "Project title" at the top are placeholders for upcoming projects.

## Deploy

Upload the folder to any static host (GitHub Pages, Netlify, Cloudflare Pages). For GitHub Pages, push the files to a repo, then enable Pages in Settings.

## Notes

- Fonts (Caveat, Lora) load from Google Fonts, so they need an internet connection.
- Your phone number is left off on purpose since the page is public.
