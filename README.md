# Oliver Club Review Archive

This is a self-contained static website for GitHub Pages. All 73 qualifying reviews are embedded directly in `index.html`; there is no database, build process, or external JavaScript dependency.

## Publish on GitHub Pages

1. Create a new public GitHub repository.
2. Upload `index.html` and `.nojekyll` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will provide the live `github.io` address.

## Connect a Cloudflare domain

After the GitHub Pages address works:

1. Add the domain to Cloudflare and use the nameservers Cloudflare provides.
2. In GitHub Pages settings, enter the custom domain.
3. Add the DNS record GitHub requests in Cloudflare.
4. Keep Cloudflare's proxy disabled until GitHub finishes issuing the HTTPS certificate; it can be enabled afterward if desired.

## Updating reviews

The review cards are embedded in `index.html`. Replace or regenerate that file when the public review archive changes.

## Important

Before publishing, review Google and Yelp's current content-display and attribution terms. The page includes source attribution and original-review links, but platform policies can change.
