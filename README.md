# Clippership Barber Shop — Static Website

A responsive, single-page static website prepared for GitHub Pages.

## Files

- `index.html` — all page content and SEO metadata
- `styles.css` — layout, typography, colors, and responsive design
- `script.js` — mobile navigation and automatic copyright year
- `assets/favicon.svg` — browser icon
- `assets/social-preview.svg` — social-sharing image
- `robots.txt` and `sitemap.xml` — basic search-engine files
- `.nojekyll` — tells GitHub Pages to serve the files directly

## Preview before publishing

Double-click `index.html`, or right-click it and open it in Chrome, Edge, Firefox, or Safari.

## Important items to verify with the business

1. Exact current weekly hours
2. Services offered
3. Whether walk-ins or appointments are preferred
4. Current pricing
5. Approved shop photographs and logo
6. Exact domain name

The public directories consulted disagree about the shop's hours, so the current website tells visitors to call or check Facebook.

## Publish to GitHub Pages

1. Upload all files and folders to the root of the GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Click **Save**.
6. Wait for GitHub to provide the temporary `github.io` address.

## Add the custom domain

After the site works at the temporary GitHub address:

1. In **Settings → Pages**, enter the custom domain.
2. At the domain registrar, add the DNS records GitHub instructs you to use.
3. Enable **Enforce HTTPS** when GitHub makes the option available.
4. Replace `YOUR-DOMAIN-HERE` in `robots.txt` and `sitemap.xml`.
5. Add this line to the `<head>` of `index.html`, using the real address:

   `<link rel="canonical" href="https://YOUR-DOMAIN-HERE/">`

## Editing

Most business text is in `index.html`. Search for the visible wording and replace it.

The main colors are at the top of `styles.css` under `:root`.

## Photos

This first version uses an original text-and-graphics design and does not copy photographs from Facebook. Once the shop supplies approved photos, add them to `assets/` and update the site.

## Business details currently used

- Clippership Barber Shop
- 1035 S Florida Ave, Suite 170, Lakeland, FL 33803
- (863) 683-2201
- Facebook: https://www.facebook.com/profile.php?id=100063651727844
