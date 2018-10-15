![SMU DataScience Logo](img/logo-2.png)
# MSDS 6306: Doing Data Science - Case Study 01

## The Borgs (Contributors)
- [Nikhil Gupta](mailto:guptan@smu.edu)
- [James Harding](mailto:harding@smu.edu)
- [Max Moro](mailto:mmoro@smu.edu)

## Background 

During past month, the talk of selling the company's brew to other breweries caught fire.  The owners sat around brainstorming on options, but too many  ideas were thrown on the table and most were not based on any research. 

## Objective

The company has the need to do some research hoping to channel the discussion of expanding the business around factual data. 

## Approach of the Analysis

The data collected contains a sample of breweries by city/state and the desired taste by state.  This will help to narrow the focus to areas where beer is seen as a necessity and a strong opinion as to the desired taste.  

## Data Sources

Follow data sources have been used:

- **Beers.csv** dataset contains a list of 2410 US craft beers. 

- **Breweries.csv**  dataset contains a list of 558 US  Breweries

- **[census.csv](https://www2.census.gov/programs-surveys/popest/datasets/2010-2017/national/totals/nst-est2017-alldata.csv)**  dataset from [census.gov](https://www.census.gov/data/tables/2017/demo/popest/nation-total.html) with estimated 2017 population count per each US State 

- **us-states.json** spatial dataset contains coordinates and geographical shape of the US States. Dataset from [PublicaMundi](https://raw.githubusercontent.com/PublicaMundi/MappingAPI/master/data/geojson/us-states.json)

## Analysis 

The full analysis has been created using R and Markdown. 

- The Source file is [TheBorgs_CaseStudy1.RMD](https://github.com/jth1911/SMU_MSDS_6306_CS1/blob/master/TheBorgs_CaseStudy1.Rmd)

- The Output file is [TheBorgs_CaseStudy1.html](https://github.com/jth1911/SMU_MSDS_6306_CS1/blob/master/TheBorgs_CaseStudy1.html)

- The GitHub Repository is https://github.com/jth1911/SMU_MSDS_6306_CS1 

## Summary of Findings

- There is a strong competition in the East and West of the country with more than 20 breweries per State

- Colorado is also a strong market with many breweries

- With few exeptions, the eastern States of the country tend to have highest ABV and IBU, in the Max and Median points of the distribution.

- There is a correlation between ABV and IBU (coefficient: +0.0351)

- There is a strong correlation between Beers and Population, with a new Beer per each 75K people

- There is a strong correlation between Breweries and Population, with a new Brewery per each 420K people

## Potential Opporunities

- We see opportunities for Expansion in states like Florida, New York, Ohio, and Georgia that are below the Correlation Line between Beer, Breweries, and Population. 

- Within above States, we would highlight New York and Ohio states having the strongest  ABV and IBU. This could be a good fit for our strategy
 

