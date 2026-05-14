dek.lit cloud assets — Phase 1 (house h3, Craftsman Bungalow)
=============================================================

Upload the `houses/` folder to your GitHub repo:
    https://github.com/jtrwells-dotcom/deklit
on the `main` branch, preserving the folder structure:

    deklit/
      houses/
        h3_day.jpg
        h3_night.jpg

Once uploaded, jsDelivr serves them automatically at:
    https://cdn.jsdelivr.net/gh/jtrwells-dotcom/deklit@main/houses/h3_day.jpg
    https://cdn.jsdelivr.net/gh/jtrwells-dotcom/deklit@main/houses/h3_night.jpg

The updated deklit_ar_v3.html already points h3 at these paths.
It will show the "Loading house photo..." placeholder until the
files are live, then render normally.

Both images were run through condense_asset.py (900px long edge,
JPEG q82) per project policy.
