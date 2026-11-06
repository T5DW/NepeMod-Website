# Nepe-Mod Website

Official website source for the **Nepe-Mod** Blood Strike PC client community project.

> A Client To Make Blood Strike Better!

## Source

All website HTML lives in [`Src/`](Src/):

- `index.html` — homepage
- `devs.html` — developers, owners, and moderators
- `contact.html` — contact information
- `developers.html` — redirect to the Devs page

This is a static website. There is no build step and no Node.js dependency. Open `Src/index.html` in a browser for a local preview.

## GitHub Pages

1. Create a GitHub repository (for example, `Nepe-Website`).
2. Upload **the contents of this `Nepe-Website` folder** to the root of the repository, including the hidden `.github` folder.
3. In GitHub, go to **Settings → Pages → Build and deployment** and choose **GitHub Actions** as the source.
4. Push to the `main` branch. The included GitHub Actions workflow publishes the `Src/` folder automatically.

GitHub identifies the project as HTML because of its `.html` files, and the workflow tells Pages which folder to publish.

Nepe-Mod is an unofficial community project and is not affiliated with the game publisher.
