# Getting started with your GitHub Pages site

You now have a simple portfolio site: a home page with clickable photos, and one page per project with a "Back" button.

## Preview on your computer

1. Open the folder `charlottealbert.github.io` in File Explorer.
2. Double-click `index.html` — it should open in your web browser.
3. Click a photo, then click **Back to all projects** to return home.

## How the site is organized

```
charlottealbert.github.io/
├── index.html          ← Home page (photo grid)
├── css/style.css       ← Colors, layout, fonts
├── images/             ← Put your photos here
└── projects/           ← One HTML file per project
    ├── example-1.html
    ├── example-2.html
    └── example-3.html
```

## Add a real project

1. **Add a photo** — Save your image in `images/`, e.g. `images/my-robot.jpg`.

2. **Create a project page** — Copy `projects/example-1.html` to something like `projects/my-robot.html` and edit:
   - The `<title>` and `<h1>`
   - The `src` on the `<img>` to point at your image
   - The paragraphs with your project description

3. **Add a card on the home page** — In `index.html`, copy one of the `<a class="project-card">...</a>` blocks and update:
   - `href` → path to your new HTML file
   - `src` → your image
   - `alt` and the title text

## Publish to GitHub Pages

1. Commit and push these files to your `charlottealbert.github.io` repository on GitHub.

2. On GitHub: open the repo → **Settings** → **Pages**.

3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.

4. Choose branch **main** (or **master**), folder **/ (root)**, then **Save**.

5. After a minute or two, your site will be live at:

   **https://charlottealbert.github.io**

(GitHub may email you when the first deploy finishes.)

## Tips

- Use photos that are roughly similar size so the grid looks neat (around 800×600 px works well).
- Keep filenames simple: lowercase, no spaces (use `my-project.jpg` not `My Project.jpg`).
- You do not need to install anything — just HTML, CSS, and images.

When you are ready to customize the look (colors, fonts), edit `css/style.css`.
