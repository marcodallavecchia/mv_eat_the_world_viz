# Description
## Concept
Visualization of typical food items on a geographical map by web scraping wikipedia page of typical food and use it to display it on interactive map.

This is used for a personal challenge of cooking typical food from random countries around the world and it's available in [my personal blog](https://marcodallavecchia.github.io/biologistsadventure/eat-the-world/)
## Content
1. national_dish_crawl.ipynb -> webscrap wikipedia page to obtain national dish information
2. country_data_merge.ipynb -> organizes all data to be used for visualization
3. map_visualization.ipynb -> generates pyplot interactive map used in the blog

## Installation
To install notebooks dependencies run:
```
conda create -n ENVNAME --file requirements.txt
```