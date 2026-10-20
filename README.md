# Video Editor Portfolio

A responsive, dark editorial-style portfolio website built with plain HTML, CSS, and JavaScript. Ready to publish with **GitHub Pages**.

## Quick start

1. Download or clone this project.
2. Open `index.html` in your browser.
3. Customize the placeholder details before publishing.

## Personalize it first

Search these files and replace the demo information:
- `index.html`: replace **Alex Rivera**, `hello@example.com`, the bio, services, and project titles.
- Project cards: replace the placeholder gradients/cards with links to your actual edits. You can link a card directly to a YouTube/Vimeo video or embed video players.
- Hero reel: replace the decorative reel panel with a video embed or a thumbnail linking to your showreel.
- `style.css`: adjust colors under `:root` to match your personal brand.

**Important:** The project visuals are placeholders, not real client work. Add your own videos and only show work you have permission to publish.

## Publish with GitHub Pages

1. Create a repository on GitHub, for example `video-editor-portfolio`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the Pages deployment. Your website URL will look like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Add a real video

For a YouTube video, you can replace a project card's `<a class="project-image ...">` element with an embed like:

```html
<div class="video-frame">
  <iframe
    src="https://www.youtube-nocookie.com/embed/YOUR_VIDEO_ID"
    title="Project title"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>
```

Add this CSS if you use the embed:

```css
.video-frame { aspect-ratio: 16 / 9; overflow: hidden; }
.video-frame iframe { width: 100%; height: 100%; border: 0; }
```

## Tech stack

- HTML5
- CSS3 (responsive layout)
- Vanilla JavaScript
- Google Fonts (Manrope + DM Mono)
