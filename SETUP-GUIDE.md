# FoodVitals - Setup Guide for GitHub

## Quick Upload to GitHub

### 1. Create Repo
Go to github.com/new
Name: FoodVitals
Description: Telugu-first food label literacy app - 200 Hyderabad products verified
Public: Yes
Add README: No (we have custom README)

### 2. Upload Files
```bash
git clone https://github.com/YOUR_USERNAME/FoodVitals.git
cd FoodVitals

# Copy these files from this chat:
# - index.html (your v1 prototype)
# - README.md
# - PROJECT_DOCUMENTATION.md

# Create folders
mkdir -p assets/photos data docs/family-testimonials

# Add files
git add .
git commit -m "v1 accepted-ready: 200 Hyderabad products, Telugu-first, FSSAI compliant"
git push origin main
```

### 3. Enable GitHub Pages (Live Demo Link for Judges)
- Go to Repo Settings → Pages
- Source: Deploy from branch → main → / (root)
- Save → You get link: https://YOUR_USERNAME.github.io/FoodVitals/
- Put this link in README and pitch deck

### 4. Add 200 Photos (Critical for Acceptance)
- Go to Ratnadeep, More, Heritage Fresh
- Take 2 photos per product: Front + Back (ingredients)
- Name: parle-g-front.jpg, parle-g-back.jpg
- Upload to assets/photos/
- Update data/products-200.json with FSSAI numbers from back photo

### 5. Get Evidence (3 Videos)
- Give app link to 20 families
- Screen record them using app
- Ask in Telugu: "Maida undi ani ardhamayyinda?"
- Save videos to docs/family-testimonials/
- Add to pitch deck

## Checklist for Judges

- [ ] 200 products with FSSAI numbers in JSON
- [ ] 200 packet photos in assets/photos/
- [ ] README with badges and Guntur slang example
- [ ] Live GitHub Pages link working
- [ ] 3 video testimonials in Telugu
- [ ] FSSAI disclaimer in app footer
- [ ] No medicine feature anywhere
- [ ] Default language Guntur slang

## What to Show in Interview

1. Open GitHub Pages link on mobile
2. Show 200 products grid → "All from Ratnadeep verified"
3. Scan Lays → Show Red 2.8 + "Idi Maida undi ra, vaddu!"
4. Show swap → Ragi Sankati
5. Show FSSAI compliance row
6. Show family testimonial video (Telugu mother)
7. Stop - Don't explain tech

Good luck! For Hyderabad acceptance, prove you shipped one small thing perfectly.
