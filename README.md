# Francesco Quatraro — personal website draft

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

## Draft scope and next additions

Content was taken from the public Google Sites homepage on 23 September 2026. This is a homepage design draft, not a verified full migration. Publications, a downloadable CV, a portrait and direct contact details have not been supplied or imported. No publication list, email address, news items or course details have been invented. Confirm current roles before publishing. The temporary link to Google Sites can be removed once migration is complete.

Suggested next additions: selected publications and working papers; CV PDF; professional portrait; institutional contact link; individual research and teaching pages when the content warrants them.

The separate HTML preview is self-contained for local review. It is not the editable Jekyll source and need not be uploaded to the repository.
