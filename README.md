# The Gilded Goblin Tavern & Inn

GitHub Pages ready static cookbook and kitchen inventory app. Publish from **main / root** in Settings → Pages.

## Files
- `index.html` responsive web app, installable on phone
- `data/recipes.json` recipe book content
- `data/inventory.json` GitHub-backed published inventory
- `assets/gilded-goblin-logo.png` place the **exact user-supplied logo** here (never regenerate)

## Inventory management
The published `data/inventory.json` now contains the reconciled November 14, 2026 kitchen inventory (312 entries), including shopping updates and recorded Hobbit stew consumption. GitHub `main` is the published inventory source of truth. Some remaining quantities are marked unconfirmed and should be verified before treating them as in stock or out of stock. Local app edits remain drafts until committed to GitHub; GitHub Pages does not write back directly without authentication/backend. ChatGPT can update the published JSON through its GitHub connector.

## Recipe pages
Add each recipe as an object in `data/recipes.json`, with optional `image` pointing to an asset under `assets/`. Keep ingredients and steps accurate; do not combine unrelated recipe cards.
