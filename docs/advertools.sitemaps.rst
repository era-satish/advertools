.. meta::
    :description lang=en:
        Download one or multiple XML sitemaps into a pandas DataFrame with
        Python. You can download URLs from a regular sitemap, or from a sitemap
        index file.

.. automodule:: advertools.sitemaps
   :members:
   :undoc-members:
   :show-inheritance:
   
   import advertools as adv

coingecko_sitemap = adv.sitemap_to_df('https://www.coingecko.com/sitemap1.xml')
coingecko_sitemap.head(10)
