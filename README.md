# Silver Jewellery Catalogue

Interactive single-page brochure for the AMI SV jewellery collection.
All product photos, codes, and prices are embedded in one self-contained
`index.html` file. No build step, no dependencies.

## What's inside
- 185 pieces across two collections (CGN and Silver)
- Gem-tier system (Pearl / Topaz / Emerald / Solitaire) mapped to price
- Vitrine tray to build a selection with a live running total
- Filters by line, type, and tier, plus code search
- Print-friendly light layout (Ctrl/Cmd+P)

## Deploy on Vercel
This is a static site. Vercel serves `index.html` at the root
automatically, no framework preset needed.

1. Push this repo to GitHub.
2. In Vercel, import the repo.
3. Framework preset: **Other**. Build command: leave empty.
   Output directory: leave empty (root).
4. Deploy.

Or from the CLI:

    npm i -g vercel
    vercel --prod

## Local preview
Open `index.html` in any browser, or:

    npx serve .
