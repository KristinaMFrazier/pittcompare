# Pittsburgh Demographics Comparison Analysis
This repo documents files needed to complete a basic comparison analysis of the demographics of Pittsburgh City, Pennsylvania.


## Installations
The following libraries and modules are required:
- pandas
- numpy
- matplotlib
- seaborn


## Project Motivation
The analysis extracts various socio-economic demographic variables to compare Pittsburgh within the context of Allegheny County and the state of Pennsylvania as a whole, as well as comparing Pittsburgh to other comparable cities: Columbus, Ohio, Cleveland, Ohio, Philadelphia, Baltimore City, and Washington, D.C. It should be noted that there is a slightly different motivation for comparing Pittsburgh to each of these cities:
- Cleveland and Columbus are two major cities in close proximity to Pittsburgh, and share a characteristic of being major cities within the Pennsylvania/Ohio region.
- Philadelphia is considered the major city of eastern half of Pennsylvania, whereas Pittsburgh is the economic center of western Pennsylvania.
- And Baltimore City and Washington, D.C. were included in this analysis because the author of this project is from the Greater Washington, D.C. area, and is interested in gaining an understanding of how Pittsburgh is different from her hometown.


## File Descriptions
The main files of this repo are:

- CensusQuickFacts.csv: This is a manually-created table of selected demographics data extracted from Census.gov's QuickFacts data tool.
- PittCompare.ipynb: this is the main analysis notebook


## How to Interact with your project
The analysis is conducted in [this notebook](https://github.com/KristinaMFrazier/pittcompare/blob/master/PittCompare.ipynb), which is divided into two major sections: the first section compares Pittsburgh City demographics within its geographic context of Allegheny County and the state of Pennsylvania, while the second compares Pittsburgh with other comparable American cities.

This analysis can be reproduced with similar structuring following the format of the CensusQuickFacts.csv file. but significant refactoring is required throughout the notebook if different variables or geographies are used.


## Licensing, Authors, Acknowledgements, etc.
The data used for this analysis was extracted from Census.gov's QuickFacts data tool presenting the 2019 Population Estimates and the 2015-2019 5-year American Community Census data products.
