# Alstonville Albums

This repository hosts static HTML album pages generated from the Lovable platform, delivered to customers via Vercel.

Each `.html` file in the root folder corresponds to a specific weekly or seasonal availability album, lookbook, or product-specific showcase.

## 🔧 Folder Structure

```
/weekly-availability.html
/hoya-range.html
/lookbook.html
/README.md
```

## 🚀 Deployment

This site is automatically deployed using [Vercel](https://vercel.com).

### Public URL Format:
Each album page is hosted at:
```
https://alstonville-albums.vercel.app/[filename].html
```

Examples:
- Weekly Availability: https://alstonville-albums.vercel.app/weekly-availability.html
- Hoya Range: https://alstonville-albums.vercel.app/hoya-range.html

## 🧠 How to Use

1. Add new `.html` album files to the root directory
2. Commit and push to `main` branch
3. Vercel auto-deploys and serves your updated album pages

## 📸 Image Hosting

All images are served from Supabase Storage:

```
https://slovwxualmrlywwvqnps.supabase.co/storage/v1/object/public/plant-images/
```

Each HTML album should reference full public Supabase URLs for reliability.

## 🔒 Access Control (optional)

While pages are public, each album includes:

- Tokenised URLs (if needed)
- Expiry date messaging (e.g. “This page expires in 30 days”)
- Optional QR code or CTA email tracking

## 📬 Contact

If you received this page as a nursery buyer or wholesaler and want to place an order:

📧 Email us: orders@alstonvilleplants.com.au  
🌱 Visit: [https://www.alstonvilleplants.com.au](https://www.alstonvilleplants.com.au)

---
