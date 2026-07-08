# Professional GitHub Pages template

This package updates the professional template using the latest `index.md` and `pub.md` content you provided.

## How to install

1. Back up your current GitHub Pages repository.
2. Copy the files in this folder into the root of your repository.
3. Commit and push to GitHub.
4. Wait for GitHub Pages to rebuild.

## Main files

- `_config.yml`: site settings
- `_layouts/default.html`: shared page layout and navigation
- `assets/css/style.css`: visual design
- `index.md`: redesigned homepage using your updated bio
- `pub.md`: redesigned projects and publications page using your updated project content

## Files you should keep in the repository root

The publication page references these files. Some were included in this package because they were available in the uploaded folder; keep any missing ones in your repository root:

- `microbial_interaction_inference_pipeline.png`
- `Genoa_connections_T1.png`
- `erasmus_example.png`
- `nicaragua_example_reports.png`
- `polbooks_hardCD_removing.png`
- `cell_fate.png`
- `gameTheory.png`

## Notes

- The template no longer uses `jekyll-theme-minimal`; the design is controlled by `_layouts/default.html` and `assets/css/style.css`.
- Existing image files in your repository will not be removed when you copy this package over them.
