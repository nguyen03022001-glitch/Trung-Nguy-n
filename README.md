# Tâm Ý Jewelry

A complete, framework-free luxury pearl jewelry storefront designed for free deployment with GitHub Pages.

## Included

- Responsive multi-page storefront: home, collection, product detail, about, contact, and bag/order request.
- Centralized product catalog in `js/products.js`.
- Client-side category filters, price sorting, global search, product detail routing, and localStorage shopping bag.
- Static order-request form that opens a prefilled WhatsApp message. Replace the number and other brand settings in `js/main.js`.
- Local SVG placeholder artwork and the optimized Tâm Ý Jewelry cover image in `images/`; replace these files with real product photos without changing the catalog structure.
- Basic SEO metadata, Open Graph tags, favicon, `robots.txt`, and `sitemap.xml`.

## Run locally

The site is static, so no server runtime or dependency install is required. You can open `index.html` directly in a browser. For the most accurate local test, run a simple static server from the project folder:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Create a GitHub repository, or use an existing empty repository.
2. Upload the complete project folder, keeping the folder structure intact.
3. Open the repository's **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then click **Save**.
6. After GitHub finishes publishing, open the Pages URL shown in the same settings panel. For this repository it will be `https://nguyen03022001-glitch.github.io/Trung-Nguy-n/`.

## Customize

Open `js/main.js` and edit `LUNARA_CONFIG` to change the brand name, currency, email, Facebook URL, WhatsApp number, and shipping message. The current display currency is USD. Edit `js/products.js` to add products or update prices and image paths.

For a project-site URL, keep all links relative as provided. If you change the repository name, update the canonical URL in `robots.txt` and `sitemap.xml`.

