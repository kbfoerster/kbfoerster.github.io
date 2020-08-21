# Kyle Foerster's Portfolio

[Kyle Foerster's Github](https://github.com/kbfoerster)

## Data Analytics

### NYCTrees Analysis
*Project is in-progress*

[This project's](https://github.com/kbfoerster/nyctrees) goal was to analyze trees located throughout New York City based on neighborhoods. Data was gathered from two censuses, one from 2005 and the other from 2015. This project includes data cleaning, dataset merging, geospatial analysis, feature extraction, and various models. This project was performed in collaboration with [a classmate](https://github.com/ElizabethSeidle)

**Notable Techniques Used:**
* Data Cleaning
   * Regex for substitution/removal
   * Dataset merges
   * Geospatial Mapping
* Machine Learning
   * CART
   * Random Forest
   * Boruta for Feature Selection
   * k-Nearest Neighbor for imputation
* Quality Checks
   * Skewness
   * Multicollinearity
   * Modality
   * Chi-squared tests

## Data Engineering

### Logstash Pipeline with NYCTrees Data
*Project is in-progress*

[This project's](https://github.com/kbfoerster/logstash_nyctrees) goal was to read a modified version of the NYCTrees data from a .csv with a Logstash pipeline. This pipeline would send the data to a local docker cluster to be further queried and analyzed. 

**Notable Technologies Used**
* Docker
* Logstash
* Elasticsearch
* Kibana
