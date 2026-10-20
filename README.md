# Francesco Quatraro — personal website

A custom responsive design for https://fquatraro-unito.github.io, using GitHub Pages' built-in Jekyll support. No JavaScript or paid services are required; the Inter and Newsreader typefaces load from Google Fonts.

## How publishing works

This repository is already live. GitHub Pages builds the site from the `main` branch (root folder) and publishes it at https://fquatraro-unito.github.io. Every commit to `main` triggers a rebuild, which usually takes a minute or two. You can follow it under the repository's **Actions** tab, and check the Pages settings under **Settings → Pages**.

### Edit in the browser

1. Open the file you want to change (for example `research.md`) on GitHub and select the pencil icon.
2. Make your edits, then choose **Commit changes** and commit directly to `main`.
3. Wait for the Pages build to finish, then reload the site.

### Replace the profile photo

The photo lives at `assets/francesco-quatraro.jpg` and is shown on the home page. To change it, open the `assets` folder, choose **Add file → Upload files**, and upload a square JPEG named exactly `francesco-quatraro.jpg` (about 720 × 720 pixels keeps the page fast). File names without spaces avoid broken links.

### Edit locally (optional)

```
git clone https://github.com/fquatraro-unito/fquatraro-unito.github.io.git
cd fquatraro-unito.github.io
# edit files, then
git add -A
git commit -m "Describe your change"
git push origin main
```

Official documentation: https://docs.github.com/en/pages

## Update your content

Each page is a Markdown file: `index.md` (home), `research.md`, `publications.md`, `teaching.md` and `profiles.md`.

- `## Heading` creates a section heading.
- `### Heading` creates a smaller heading.
- `- Text` creates a list item.
- `[Link text](https://example.org)` creates a link.
- Keep the front matter (the lines between `---` at the top of each page) intact so the layout and navigation work.
- Colours, spacing and typography live in `assets/style.css`.
- The header, navigation and footer live in `_layouts/base.html`; the home-page hero, photo and contact block live in `_layouts/home.html`.
- Every `## Heading` in a page becomes its own numbered section (heading on the left, text on the right), so adding a section only needs a new `##` heading.
- Site title and metadata live in `_config.yml`.

## Migrated content

The site is organised into a home page, research, publications, teaching and roles, and profiles and links. The content was migrated from the public Google Sites profile on 23 September 2026. The publications page preserves the three source research strands, all 44 representative publications, and their DOI links.

The previous Google Sites profile remains linked from the profiles page for reference. Current roles, institutional links and external researcher profiles should be reviewed periodically.
