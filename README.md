# Vidoré

A single-page site — a love letter, made public.

## What's inside
```
index.html
assets/
  css/style.css
  js/main.js
  img/vidore.jpg
```

- **No build step.** It's plain HTML/CSS/JS — open `index.html` in a browser and it works.
- The letter reveals one line at a time as you scroll, ending on "I love you the most."
- The small speaker icon (bottom-right) is optional — it plays a soft ambient tone synthesized directly in the browser (no audio file). Off by default.

## How to put this on GitHub Pages

1. **Create a new repository** on GitHub — e.g. `vidore` (or `yourusername.github.io` if you want it at the root of your GitHub domain).
2. **Upload these files**, keeping the folder structure exactly as-is (the `assets` folder and everything inside it needs to stay next to `index.html`).
   - Easiest way: on the repo's GitHub page, click **Add file → Upload files**, then drag this whole folder's contents in.
3. Go to the repo's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` (or `master`) and `/ (root)`, then **Save**.
6. GitHub will give you a live URL after a minute or two, usually:
   `https://yourusername.github.io/vidore/`

## Changing anything later
- **The words**: open `index.html`, each line of the letter is its own `<section class="line">...</section>` block.
- **The photo**: replace `assets/img/vidore.jpg` with a new image of the same filename, or update the `src` in `index.html`.
- **Colors**: all colors are defined once at the top of `assets/css/style.css` under `:root`.
