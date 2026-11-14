# The Gilded Goblin Tavern & Inn

GitHub Pages ready static cookbook and kitchen inventory app. Publish from **main / root** in Settings → Pages.

## Files
- `index.html` responsive web app, installable on phone
- `data/recipes.json` recipe book content
- `data/inventory.json` GitHub-backed published inventory
- `assets/gilded-goblin-logo.png` place the **exact user-supplied logo** here (never regenerate)

## Inventory migration
The included inventory JSON is a **partial starter**, not a complete migration of the master spreadsheet. In the app, open **The Pantry → Import inventory** and select `Kitchen_Inventory.xlsx` to load the full sheet. Then **Export JSON** and commit the exported file to `data/inventory.json` on GitHub. After that, the repository is the source of truth. Device edits are local drafts until committed; GitHub Pages cannot directly write back to GitHub without authentication/backend. ChatGPT can edit `data/inventory.json` using its GitHub connector.

## Recipe pages
Add each recipe as an object in `data/recipes.json`, with optional `image` pointing to an asset under `assets/`. Keep ingredients and steps accurate; do not combine unrelated recipe cards.
