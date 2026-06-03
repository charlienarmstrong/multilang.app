# MultiLang Public Deployment

This folder is ready to publish as a static website.

## Files to upload

- `index.html` is the public app entry point.
- `multilang.html` is a backup copy of the same app.
- `CNAME` sets the intended custom domain to `multilang.app`.

## Fastest path

1. Register `multilang.app` with a domain registrar.
2. Create a static site on Netlify, Vercel, GitHub Pages, or Cloudflare Pages.
3. Upload or deploy the contents of this `outputs` folder.
4. In the hosting provider, add `multilang.app` as the custom domain.
5. In the registrar DNS settings, point `multilang.app` to the hosting provider.
6. Wait for HTTPS to finish provisioning.

## Recommended providers

- Netlify Drop is easiest for a manual upload.
- Vercel is a good fit once this becomes a full app project.
- Cloudflare Pages is good if the domain is registered through Cloudflare.
