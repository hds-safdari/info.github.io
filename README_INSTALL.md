# GitHub Pages single-page template

This package puts the bio and portrait area first, then places selected projects and publications below it on the same homepage.

## Install

1. Unzip the package.
2. Copy the files inside this folder directly into the GitHub Pages publishing root.
   - If GitHub Pages is set to publish from `/ root`, put `index.html` directly in the repository root.
   - If GitHub Pages is set to publish from `/docs`, put `index.html` directly inside `docs/`.
3. Commit and push.
4. In GitHub, check **Settings → Pages** and confirm the selected branch and folder.

## Add your personal photo

The page currently looks for a file named:

```text
profile.jpg
```

Add your portrait to the same folder as `index.html` and name it exactly `profile.jpg`.

If your file is called something else, either rename it or edit this line in `index.html`:

```html
<img class="portrait" src="profile.jpg" alt="Portrait of Hadiseh Safdari">
```

For example, for `hadiseh-photo.png`, change it to:

```html
<img class="portrait" src="hadiseh-photo.png" alt="Portrait of Hadiseh Safdari">
```

Until a personal photo is added, the page falls back to `profile.svg`, a simple initials placeholder.

## Project figures

This package includes the image files that were available in the chat. Your publications also reference these existing files:

- `Genoa_connections_T1.png`
- `erasmus_example.png`
- `nicaragua_example_reports.png`
- `polbooks_hardCD_removing.png`
- `cell_fate.png`
- `gameTheory.png`

If those files are already in your GitHub repository, leave them in the same folder as `index.html`. If they are missing, the page will simply hide the missing figure blocks.

## Structure

- `index.html` — main single-page site
- `pub.html` — redirects old publication-page links to `index.html#publications`
- `assets/css/style.css` — site styling
- `profile.svg` — fallback portrait placeholder
- `source_markdown/` — copies of your latest uploaded Markdown sources

No CV link is included.
