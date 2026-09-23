# Francesco Quatraro — personal website

A custom responsive design for https://fquatraro-unito.github.io, using GitHub Pages' built-in Jekyll support. No JavaScript, external fonts or paid services are required.

## Publish through the GitHub website

1. Sign in as `fquatraro-unito`.
2. Check your repositories. If `fquatraro-unito.github.io` exists, review and back up its content before uploading anything. Otherwise create a **public** repository with exactly that name, and initialize it with a README.
3. Extract this ZIP. In the repository select **Add file → Upload files**. Upload the contents of the `website` folder, including `_layouts` and `assets`. Do not upload the ZIP itself or an enclosing `website` folder. Replace the initial README with this one if appropriate.
4. Commit the upload to `main`.
5. Open **Settings → Pages**. Under Build and deployment choose **Deploy from a branch**, select **main** and **/ (root)**, then Save.
6. Wait for the Pages build to complete (it may take up to 10 minutes), then visit https://fquatraro-unito.github.io.

Official instructions: https://docs.github.com/en/pages/quickstart

## Update your content

Open `index.md` in GitHub and select the pencil icon. Edit the prose, then commit the changes. GitHub rebuilds the website automatically.

- `## Heading` creates a section heading.
- `### Heading` creates a smaller heading.
- `- Text` creates a list item.
- `[Link text](https://example.org)` creates a link.
- Keep the three-line front matter at the beginning and the heading IDs (`{: #research }`, etc.) intact so the navigation works.
- Colours, spacing and typography live in `assets/style.css`.
- The header, introductory text and footer live in `_layouts/default.html`.
- Site title and metadata live in `_config.yml`.

## Migrated content

The site is organised into a home page, research, publications, teaching and roles, and profiles and links. The content was migrated from the public Google Sites profile on 23 September 2026. The publications page preserves the three source research strands, all 44 representative publications, and their DOI links.

The previous Google Sites profile remains linked from the profiles page for reference. Current roles, institutional links and external researcher profiles should be reviewed periodically.
