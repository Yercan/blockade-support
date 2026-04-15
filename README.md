# Blockade — Support site (GitHub Pages)

This folder contains a static **Support** page for the Blockade iOS app, suitable for **App Store Connect → Support URL**.

## Support URL (after publishing)

Use this URL in App Store Connect once GitHub Pages is enabled:

**`https://yercan.github.io/blockade-support/`**

(Replace `blockade-support` with your actual repository name if different.)

## How to publish on GitHub

1. Create a new public repository on GitHub, e.g. **`blockade-support`** under [github.com/Yercan](https://github.com/Yercan).
2. Upload the contents of this **`support/`** folder to the **root** of that repository (so `index.html` is at the repo root).
3. In the repo: **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose **branch `main`** (or `master`) and folder **`/ (root)`**, then **Save**.
6. After a minute, the site will be live at `https://yercan.github.io/<repo-name>/`.

## App Store Connect

- **Support URL:** `https://yercan.github.io/blockade-support/`
- **Marketing URL (optional):** Same URL or your GitHub profile `https://github.com/Yercan`

## Editing content

- Edit **`index.html`** for English support text, FAQ, and contact hints.
- Keep contact paths realistic: add a public email or a dedicated “Issues” repo link when you have one.
