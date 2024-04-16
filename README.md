# Project info
```
Author: Izzat Zanail - izzat.zanail@gmail.com
Language: Python 3.12
Created: 2024-03-21
Updated: 2024-04-05
Project: Transfermarkt Malaysia Super League Data Scraper
Description: Extract MSL football teams and players data from Transfermarkt
```

# Introduction

Web scraping project that extracts Malaysian Super League (MSL) football teams and players data from season 2017 to 2024/25 from Transfermarkt website such as Team Name, Player Name, Value in EUR, Position, Numbers and Nationality, cleans up the data for further analysis, and stores data in CSV files.





# Process

## 1) Import required libraries

- requests
- BeautifulSoup
- pandas


## 2) Extract team page links for each season

Preview of dataset of extracted Transfermrkt page links for each team and each season:

<img src="/img/TeamPagesLink.png">

## 3) Create a dataframe for the extracted team links


## 4) Export the "Team Links" dataframe to csv file


## 5) Scrape all player data from every teams, from each season - based on links that were previously scraped


## 6) Perform data cleaning


## 7) Create the final dataframe for the full player data from all teams and all season since 2017 until 2024/25

Preview of the final dataset:

<img src="/img/FinalDataset.png">

## 8) Export the final dataframe to csv file



