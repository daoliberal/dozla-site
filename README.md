# Dozla — Website

Minimal static site for the Dozla iOS app: `index.html`, `privacy.html`, `terms.html`, plus a shared `style.css`. No build step, no JS frameworks. Every page is bilingual (Turkish primary, English via a `#tr` / `#en` toggle, pure CSS — no JavaScript).

## Publish to GitHub Pages

1. Create a new GitHub repository named `dozla-site` (public).
2. From this directory, add the remote and push:

   ```sh
   git remote add origin https://github.com/<user>/dozla-site.git
   git branch -M main
   git push -u origin main
   ```

3. In the repository, go to **Settings → Pages**, and under **Build and deployment** choose **Deploy from a branch**, with branch `main` and folder `/ (root)`. Save.
4. After a minute or two, the site will be live at:

   - `https://<user>.github.io/dozla-site/`
   - `https://<user>.github.io/dozla-site/privacy.html`
   - `https://<user>.github.io/dozla-site/terms.html`

Replace `<user>` with your GitHub username.
