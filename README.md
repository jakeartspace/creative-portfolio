# Jakeartspace — Creative Design Studio

A playful, bold portfolio for Jakeartspace, using a sunshine-yellow and deep-navy identity with original portfolio artwork.

## Portfolio categories
- Social Media & Digital Campaigns
- Logo & Visual Identity
- Packaging Design
- Apparel & Merchandise
- Editorial & Print Design
- Banner & Event Graphics
- Illustration
- Corporate & Certificate Design

## Add the portfolio images
1. Download the optimized asset package shared in the ChatGPT conversation.
2. Upload the file named `portfolio-assets.zip` to the root of this repository.
3. Commit the upload to the `main` branch.
4. The GitHub Actions workflow at `.github/workflows/pages.yml` extracts the image files and manifest during deployment.

The package contains optimized WebP previews and a `portfolio-manifest.json` file. Original PSD/AI/INDD working files are not included in the website package.

## Enable GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. The workflow will publish the site after `portfolio-assets.zip` is uploaded.
4. The expected website address is `https://jakeartspace.github.io/creative-portfolio/`.

## Website details
- Responsive layout for desktop and mobile.
- Category filters and full-size artwork preview.
- Built with HTML, CSS and vanilla JavaScript.
- Contact details can be added before launch.
