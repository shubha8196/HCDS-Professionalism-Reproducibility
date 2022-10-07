# data-512-homework_1: HW1- Professionalism & Reproducibility

This repository contains all the required materials for Homework 1 of DATA 512- Human Centered Data Science course (Autumn 2022) offered by the MSDS program at the University of Washington. 

## Goal

The goal of this assignment is to construct, analyze, and publish a dataset of monthly article traffic for a select set of pages from English Wikipedia from January 1, 2015 through September 30, 2022.

## Data Utilized

In order to achieve the goal defined above, the data has been collected through 
[Pageviews API](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews). 
The Pageviews API ( [documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), [endpoint](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through the previous complete month.
And the dinosaur_genera.cleaned.SEPT.2022.xlsx- This is the subset of the English Wikipedia that represents a large number of [dinosaur related articles](https://docs.google.com/spreadsheets/d/1zfBNKsuWOFVFTOGK8qnTr2DmHkYK4mAACBKk1sHLt_k/edit?usp=sharing)

## Repository Distribution

```
data-512-homework_1/
  |- README.md
  |- LICENSE
  |- DATA 512-HW1-Jupyter Notebook.ipynb
  |- JSON data files/
    |- dino_monthly_mobile_201507-202209.json
    |- dino_monthly_desktop_201507-202209.json
    |- dino_monthly_cumulative_201507-202209.json
  |- Analysis Graphs/
    |- Plot1- article_maxmin_avg_views.jpg
    |- Plot2- article_peak_page_views.jpg
    |- Plot3- article_fewest_months.jpg
  |- Data
    |- dinosaur_genera.cleaned.SEPT.2022.xlsx
```


 the data for the articles with highest and lowest average page views for both desktop and mobile

## Outputs Obtained

JSON files:
dino_monthly_desktop_201507-202209.json - This JSON file contains all the Dinosaurs articles page data for desktop access type.
dino_monthly_mobile_201507-202209.json - This JSON file contains all the Dinosaurs articles page data for mobile access type.
dino_monthly_cumulative_201507-202209.json - This JSON file contains the cumulative page views data for all the Dinosaurs articles for both desktop and mobile type of access. 

Plot1- article_maxmin_avg_views.jpg : For Top 10 Peak Page Views - This is a time series plot displaying the data for the top 10 articles with highest page views for both desktop and mobile access types.

Plot2- article_peak_page_views.jpg : 

Plot3- article_fewest_months.jpg : 

## Author
- [Shubha Changappa Palachanda](https://github.com/shubha8196)
