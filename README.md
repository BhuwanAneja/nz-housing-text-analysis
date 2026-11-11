# NZ Government Housing Communications (2020–2023)

Collected and analysed New Zealand Government press releases and speeches about housing to find which themes the government talked about most.

## Data
- 60+ housing-related press releases and speeches from the Beehive (beehive.govt.nz), 2020–2023
- Minister information from the **Wikipedia API**

## Methods
- Checked the site's `robots.txt` and copyright terms before collecting data. Pages were saved manually rather than scraped repeatedly.
- Extracted titles, dates, ministers, portfolios and summaries from the HTML with **rvest**
- Pulled minister data from the Wikipedia API with **jsonlite**, then cleaned and merged the two sources
- Classified each release into six housing themes with keyword rules in **stringr**
- Visualised theme frequency with ggplot2

## Findings
Government housing communication was dominated by **building supply, disaster/flood housing and renting**. Affordability and public housing came up less often.

## Tools
R, rvest, jsonlite, stringr, dplyr, ggplot2

## Files
- `report.html` – full report with code (download and open in a browser)
