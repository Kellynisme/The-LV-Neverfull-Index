# Synopsis
The objective of this assignment is to look at the price difference of the LV Neverfull bag across different countries. We looked at how this price difference was affected by the importing distance of each country from the manufacturing location. Since the majority of the LV workshops for bag manufacturing are located in Europe, we chose Luxembourg as the origin location, from which these distances are measured, because Luxembourg is close to Central Europe'.

# The Creation of the Index
## 1. Importing data
We scraped the table 

<i>lv_price = scrape_table(table1)

lv_price_cad=lv_price.apply(lambda x:x*1.3544, 'Price in USD$')

lv_price=lv_price.with_column('Price in CAD$',lv_price_cad)

lv_price</i>

This is our assignment 3
