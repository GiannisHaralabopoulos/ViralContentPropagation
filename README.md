# ViralContentPropagation

A collection of scraped submissions from Reddit, ImgUr, and Youtube, as described in:
  - https://www.sciencedirect.com/science/article/pii/S1084804515001307
  - https://arxiv.org/abs/1712.02245

The data is named as **OriginatingDomain_ScrappedFromSubreddit.txt**

## Data headers

Scrapped data is stored in tab separated .tx files.

The headers are as follows:
- Reddit Url
- Domain Url
- Submitted Subreddit
- Sum of positive and negative votes in reddit
  - Formatted as a ":" separated timeseries
- Twitter mentions of either Reddit or Domain Url
  - Formatted as a ":" separated timeseries
- Facebook mentions of either Reddit or Domain Url
  - Formatted as a ":" separated timeseries
- Domain views
  - Formatted as a ":" separated timeseries
- Identifier
