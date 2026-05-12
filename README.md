# Rishav Research Portfolio

A personal research portfolio and blog built with Quarto.

## Local preview

```bash
quarto preview
```

## Render site

```bash
quarto render
```

## Resume link

The resume link is currently a placeholder in `_quarto.yml` and `index.qmd`.
Replace:

```text
https://drive.google.com/file/d/YOUR_RESUME_FILE_ID/view?usp=sharing
```

with your actual Google Drive resume link.

Make sure the Google Drive file sharing setting is:

```text
Anyone with the link can view
```

## Profile photo

Add your photo here:

```text
assets/images/profile.jpg
```

If you use a different filename, update this line in the script or in `index.qmd`:

```text
PROFILE_IMAGE="assets/images/profile.jpg"
```

## Deploy

Push this repository to GitHub and enable GitHub Pages.
