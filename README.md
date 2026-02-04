# Ari Nails - Website

A clean, bold website for Ari Nails salon in downtown Hilo, Hawaii.

## Quick Deploy

### Vercel (Recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your GitHub repo
4. Deploy (zero config needed)

### GitHub Pages
1. Go to repo Settings → Pages
2. Set source to `main` branch, `/public` folder
3. Save and wait for deploy

## Local Development

```bash
# Install serve globally (one time)
npm install -g serve

# Run locally
npx serve public

# Opens at http://localhost:3000
```

## Structure

```
ari-nails-site/
├── public/
│   └── index.html    # Full website (single file)
├── package.json
├── vercel.json
└── README.md
```

## Customization

Everything is in `public/index.html`:
- **Colors**: Edit CSS variables at top (--teal, --black, etc.)
- **Fonts**: Using Syne (headers) + DM Sans (body) from Google Fonts
- **Content**: All text is plain HTML, easy to edit
- **Offer**: Change the promo in the `.offer` section

## Features

- 📱 Mobile-first responsive design
- 📞 Sticky call-to-action phone button
- ⚡ Single-file, no build step, instant load
- 🎨 Bold typography (Syne + DM Sans)
- ✨ Clean, modern aesthetic

---

Made for Ari Nails · Hilo, Hawaii
