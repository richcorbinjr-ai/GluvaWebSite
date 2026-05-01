# Gluva Website

Employer Risk Intelligence Platform — marketing website.

## Structure

```
gluva-website/
├── index.html          # Main landing page
├── contact.html        # Contact / early access form
├── privacy.html        # Privacy policy
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # Nav, scroll, form behavior
└── README.md
```

## Deploying to GitHub Pages

1. Push this folder to a GitHub repository
2. Go to Settings → Pages
3. Set source to `main` branch, root folder
4. Your site will be live at `https://yourusername.github.io/gluva-website`

## Deploying to Custom Domain (gluva.com)

1. Add a `CNAME` file to the root with your domain: `gluva.com`
2. In GitHub Pages settings, add your custom domain
3. Update your DNS: add a CNAME record pointing to `yourusername.github.io`

## Contact Form

The contact form currently shows a success message on submit. To connect it to a real email backend, replace the `handleSubmit` function in `js/main.js` with a POST request to a service like:
- **Formspree**: https://formspree.io — add `action="https://formspree.io/f/YOUR_ID"` to the form
- **Netlify Forms**: Works automatically if hosted on Netlify
- **EmailJS**: Client-side email sending

## Fonts

Uses Google Fonts:
- Playfair Display (display headings)
- DM Sans (body text)
- DM Mono (labels, badges, monospace elements)

## Colors

| Token   | Hex       | Usage                  |
|---------|-----------|------------------------|
| --navy  | #1B3A6B   | Primary dark           |
| --teal  | #0D7A8E   | Accent / CTA           |
| --green | #15803D   | Success states         |
| --gold  | #D97706   | Highlight metrics      |
| --slate | #475569   | Body text              |
| --dark  | #0F1F3D   | Hero / CTA backgrounds |

## Notes

- No names of founders included per brief
- Dashboard preview uses representative data — clearly labeled as such
- "In Development" badge on dashboard section sets honest expectations
- Research citations are accurate and sourced from project study files
- Early access CTA throughout — captures interest before full launch
