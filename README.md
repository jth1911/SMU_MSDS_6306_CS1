
# Market Analysis for BorgsBeer.com

## Created by Collective.ai (Contributors)
- [Nikhil Gupta](mailto:guptan@smu.edu)
- [James Harding](mailto:harding@smu.edu)
- [Max Moro](mailto:mmoro@smu.edu)

# Background

The BeerBorg.com is a Beer company that combines the  love for Star Trek and beer.  Who would have ever imagined someone would get tired of the typical draft beer and decide to brew our on own beer.  It started out as a small group competition that resulted in picking a few brews, purchasing a building to meet and finally a full blown brewery that attracts not just Star Wars fans but fans of science fiction in general.  The Borg has assimilated 10 different draft beers and 2 seasonal beers. 

# Objective 

Last month, the talk of selling the brew to other breweries caught fire, BeerBorgs approached Collective.ai to perform analysis about the market. Way too many ideas were thrown on the table and most were not based on any research.  In an attempt to further the discussion, we (James, Max and Nikhil) decided to do some research hoping to channel the discussion around factual data to best of our knowledge.  The data we have collected contains a sample of breweries by city/state and the desired taste by state, including correlations between ABV/IBU and between population and market size.  This will help to narrow the focus to areas where beer is seen as a necessity and a strong opinion as to the desired taste.  

# Code Book 

## Approach of the Analysis

The data collected contains a sample of breweries by city/state and the desired taste by state.  This will help to narrow the focus to areas where beer is seen as a necessity and a strong opinion as to the desired taste.  

## Data Sources

Follow data sources have been used:

- **Beers.csv** dataset contains a list of 2410 US craft beers. 

- **Breweries.csv**  dataset contains a list of 558 US  Breweries

- **[census.csv](https://www2.census.gov/programs-surveys/popest/datasets/2010-2017/national/totals/nst-est2017-alldata.csv)**  dataset from [census.gov](https://www.census.gov/data/tables/2017/demo/popest/nation-total.html) with estimated 2017 population count per each US State 

- **us-states.json** spatial dataset contains coordinates and geographical shape of the US States. Dataset from [PublicaMundi](https://raw.githubusercontent.com/PublicaMundi/MappingAPI/master/data/geojson/us-states.json)

The sources data have been merged to create a set of analytics to show the number of breweries and beers per State, correlation of ABV, IBU and  population by State. 

## Analysis 

The full analysis has been created using R and Markdown. 

- The Source file is [TheBorgs_CaseStudy1.RMD](https://github.com/jth1911/SMU_MSDS_6306_CS1/blob/master/TheBorgs_CaseStudy1.Rmd)

- The Output file is [TheBorgs_CaseStudy1.html](http://htmlpreview.github.io/?https://github.com/jth1911/SMU_MSDS_6306_CS1/blob/master/TheBorgs_CaseStudy1.html)

- The GitHub Repository is https://github.com/jth1911/SMU_MSDS_6306_CS1 

# Summary of Findings

- There is a strong competition in the East and West of the country with more than 20 breweries per State

- Colorado is also a strong market with many breweries

- With few exeptions, the eastern States of the country tend to have highest ABV and IBU, in the Max and Median points of the distribution.

- There is a correlation between ABV and IBU (coefficient: +0.0351)

- There is a strong correlation between Beers and Population, with a new Beer per each 75K people

- There is a strong correlation between Breweries and Population, with a new Brewery per each 420K people

# Potential Opportunities

- We see opportunities for Expansion in states like Florida, New York, Ohio, and Georgia that are below the Correlation Line between Beer, Breweries, and Population. 

- Within above States, we would highlight New York and Ohio states having the strongest  ABV and IBU. This could be a good fit for our strategy
 

