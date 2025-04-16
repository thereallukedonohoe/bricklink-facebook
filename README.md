# BrickLink Facebook Feed (GitHub Pages)

This GitHub Action runs nightly at 2am AWST and:

- Pulls your full BrickLink inventory
- Generates a Meta Commerce Manager–compatible CSV feed
- Publishes it via GitHub Pages at:

https://<your-username>.github.io/<your-repo>/meta_product_feed.csv

## Setup Instructions

1. Enable GitHub Pages:
   - Go to your repo Settings → Pages
   - Source: `gh-pages` branch → root

2. Wait 1–2 minutes for the page to activate

3. In Facebook Commerce Manager:
   - Go to **Catalog → Product Data Sources**
   - Choose **Scheduled Feed**
   - Paste the feed URL above
   - Set to update daily

That's it! 🧱
