# Empowerkit Website - Static Version

This repository contains the static HTML version of the Empowerkit website, converted from WordPress for hosting on GitHub Pages.

## 📁 Structure

```
docs/
├── index.html              # Homepage
├── packages/               # Pricing page
├── contact-us/             # Contact page (with support@empowerkit.com)
├── blog/                   # Blog post
├── terms-of-use/          # Terms of use
├── wp-content/            # WordPress assets (CSS, JS, images)
├── wp-includes/           # WordPress core assets
└── .nojekyll              # Tells GitHub Pages to serve as-is
```

## 📝 Pages

- **Home**: Main landing page with features and testimonials
- **Pricing**: Package information (`/packages/`)
- **Contact Us**: Contact information with support email (`/contact-us/`)
- **Blog**: Single blog post about MLM compliance (`/blog/`)
- **Terms of Use**: Legal terms (`/terms-of-use/`)

## 🔧 How to Update Content

Since this is a static HTML site, you'll need to edit the HTML files directly:

### Updating Text Content

1. Navigate to the page you want to edit in the `docs/` directory
2. Open the `index.html` file in that directory
3. Find the text you want to change (search for the current text)
4. Update the text
5. Commit and push changes:
   ```bash
   git add docs/
   git commit -m "Update content on [page name]"
   git push origin main
   ```

### Updating Images

1. Add new images to `docs/images/` or `docs/wp-content/uploads/2025/08/`
2. Update the image path in the HTML file:
   ```html
   <img src="/images/your-new-image.jpg" alt="Description">
   ```
3. Commit and push changes

### Updating Contact Email

The contact email is currently set to `support@empowerkit.com` in `/docs/contact-us/index.html`. To change it:

## 📧 Contact

For support and inquiries: support@empowerkit.com

## 📜 License

This site contains proprietary content. All rights reserved.
