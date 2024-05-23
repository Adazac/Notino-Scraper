# Notino-Scraper

## Info
This scraper gets information about products from https://www.notino.cz/zubni-pasty/.

It is done using Python in Jupyter Notebooks.

"scraper.ipynb" scrapes "Brand", "Name", "Description", "Price", "Discount", "Product URL", "Image" of a product and saves it into "notino_raw.csv".

"transformation.ipynb" calculates "Discount Amount", adds "Country", "Currency" and "Scraped at" and saves the data into "notino_transformed.csv".
