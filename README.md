# Mandsaur Catalogue - Riddhi Siddhi Store

A free product catalogue page (55 items) plus the CSV for Meta Commerce Manager / WhatsApp Business.

- Website: https://mtarvecha660-lgtm.github.io/mandsaur-catalogue/
- Each item has its own link: .../#<id> (for example .../#daawat-dubar)
- `catalog_products.csv` - the file you upload to Meta Commerce Manager. Every link and image_link points to this GitHub site.
- `NOTES.md` - where each price, brand and photo came from, and what still needs checking.

## Files
- `index.html` - the whole page. All items are in the `ITEMS` list near the top.
- `images/<id>.jpg` - one photo per item (sample photos).
- `catalog_products.csv` - the Meta catalogue file.

## How to change a price
1. On GitHub open `index.html`, click the pencil icon (Edit).
2. Find the item in the `ITEMS` list and change its `"price"` number.
3. Commit changes. The site updates in about 1 minute.
4. Open `catalog_products.csv`, edit the same item's `price` column (format `480.00 INR`), commit, then re-upload the CSV in Meta Commerce Manager.

## How to replace a sample photo
1. Take a clear square-ish JPG photo, at least 500x500 pixels.
2. Name it exactly like the old one (for example `makhana-bold.jpg`).
3. Open the `images` folder on GitHub > Add file > Upload files > drop the photo > Commit. It replaces the old photo.
