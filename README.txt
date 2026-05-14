dek.lit cloud assets — Phase 2 (remaining 8 houses)
====================================================

This completes the house-photo migration. Upload the `houses/` folder
contents into the EXISTING `houses/` folder in your repo:
    https://github.com/jtrwells-dotcom/deklit   (main branch)

These 16 files join h3_day.jpg / h3_night.jpg already there:

    houses/
      h1_day.jpg    h1_night.jpg     (Modern Cedar)
      h2_day.jpg    h2_night.jpg     (White Bungalow)
      h5_day.jpg    h5_night.jpg     (Stone Country)
      h8_day.jpg    h8_night.jpg     (Stucco Ranch)
      h9_day.jpg    h9_night.jpg     (Blue Cape Cod)
      h10_day.jpg   h10_night.jpg    (Craftsman Gables)
      h11_day.jpg   h11_night.jpg    (Spanish Villa)
      h14_day.jpg   h14_night.jpg    (Stucco Craftsman)

UPLOAD STEPS (GitHub website):
  1. Open the `houses` folder in your repo (click it on the main page).
  2. Click "Add file" -> "Upload files".
  3. Because you're already INSIDE the houses folder, you can drag the
     16 loose .jpg files straight onto the drop zone — they'll land in
     houses/ automatically, no rename needed this time.
  4. Scroll down, "Commit directly to the main branch", Commit changes.

VERIFY (give jsDelivr 1-2 min, then paste in browser):
  https://cdn.jsdelivr.net/gh/jtrwells-dotcom/deklit@main/houses/h1_day.jpg
  https://cdn.jsdelivr.net/gh/jtrwells-dotcom/deklit@main/houses/h9_night.jpg

The updated deklit_ar_v3.html already points all 9 houses at these
paths. All images run through condense_asset.py (900px long edge,
JPEG q82) per project policy.
