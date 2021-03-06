# ViralContentPropagation

A collection of scraped submissions from Reddit, ImgUr, and Youtube, as described in:
  - [Lifespan and propagation of information in On-line Social Networks: A case study based on Reddit](https://www.sciencedirect.com/science/article/pii/S1084804515001307)
  - [Viral content propagation in Online Social Networks](https://arxiv.org/abs/1712.02245)

**Please cite the aforementioned papers, if you find the dataset useful for your research.**

## Data filename

The data is named as **OriginatingDomain_ScrappedFromSubreddit.txt**

## Data headers

Scrapped data is stored in "tab" separated .txt files.

The headers are as follows:
- Reddit Url
- Domain Url
- Submitted in Subreddit
- Sum of positive and negative votes in reddit
  - Formatted as a ":" separated timeseries
- Twitter mentions of either Reddit or Domain Url
  - Formatted as a ":" separated timeseries
- Facebook mentions of either Reddit or Domain Url
  - Formatted as a ":" separated timeseries
- Domain views
  - Formatted as a ":" separated timeseries
- Identifier
