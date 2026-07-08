# GitHub Pages static root fix

This package is designed to avoid the GitHub Pages root 404 error by placing a real `index.html` at the top level of the publishing source.

## Install

1. Open the zip.
2. Copy the CONTENTS of this folder into the publishing source of your GitHub Pages repository.
   - If Pages is set to publish from `main` / root, put these files directly in the repository root.
   - If Pages is set to publish from `main` / docs, put these files directly inside `docs/`.
3. Do not upload the outer folder itself as a subfolder.
4. Commit and push.
5. In GitHub, go to Settings > Pages and confirm the source branch/folder matches where you put the files.

## Important files

- `index.html`: homepage entry file GitHub Pages can serve at the root URL.
- `pub.html`: projects and publications page.
- `assets/css/style.css`: visual styling.
- `.nojekyll`: keeps this as a static HTML site.
- `source_markdown/`: editable copies of the Markdown source used to generate the HTML. These are for your reference only and are not required for publishing.

## Images

This package includes the images that were available in the uploaded folder. Your publications page still references these additional figure files, which should remain in the same publishing folder if you want them displayed:

- `Genoa_connections_T1.png`
- `erasmus_example.png`
- `nicaragua_example_reports.png`
- `polbooks_hardCD_removing.png`
- `cell_fate.png`
- `gameTheory.png`

No CV link is included.
