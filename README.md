# MSIG Loading Animation Library

A small static HTML/CSS repo for sharing MSIG loading animation options with colleagues.

## What is included

- `index.html` — main gallery page
- `styles.css` — layout styles and generic loading animation CSS
- `logo-animations/` — place your 3 existing logo-based HTML files here

## Add your existing logo animations

Upload these files into the `logo-animations` folder:

```text
MSIG-loader-circle.html
MSIG-loader-fill.html
MSIG-loader-stroke.html
```

The gallery already has iframe preview cards that point to these filenames.

## Preview locally

Open the folder in VS Code, then use the Live Server extension.

Or open `index.html` directly in a browser.

## Publish to GitHub Pages

1. Create a new public repo on GitHub.
2. Upload all files from this folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.

Your page should be available at:

```text
https://maihnh.github.io/YOUR_REPO_NAME/
```

## Color notes

The generic loaders use `#5a25dd` as the primary color, plus lighter purple shades. The preview surface is designed around a white 90% opacity background.
