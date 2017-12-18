# DATA 512 Final Project Report: Analysis of World University Rankings
## Abstract
The purpose of this project is to perform an exploratory analysis on rankings of global universities that can provide applicants a guideline in many different aspects to help them make better decisions on their applications. The project also strives to suggest improvements in the areas covered by the ranking systems to make them stronger. However, often ranking a university is a difficult and controversial practice due to many influences, including geographical coverage, institutional coverage, the way indicators are calculated, etc. Thus, biases caused by such factors are taken into consideration. Two global university ranking datasets which producers are from very different places are used to find out underlying biases among different ranking systems. 

Overall, citation scores have relatively obvious impacts on rankings. On the contrary, student staff ratio didn’t show a clear correlation with rankings. High ranked universities are more likely from developed countries. However, population is not a significant contributor to rankings. We also found bias does exist among different ranking systems.

## Data
### 1. University Ranking Data

1.1 Times Higher Education World University Ranking (“timesData.csv”)
Times Higher Education is a well-known global university ranking system which mainly focuses on a lot of non-English educational institutions and their commercialization. It collaborated with Thomson Reuters and started to use its own methodology since 2011. The dataset, “timesData.csv”, contains 2603 rows and 14 columns (13 performance indicators and 1 column for year). The performance indicators cover 5 major fields: teaching, research, citations, income, international outlook. I’ll use this dataset as a prime dataset to answer the majority of research questions. Columns found in the dataset are listed below:
![the_data](https://user-images.githubusercontent.com/26759376/34130268-0dc77d0c-e3fc-11e7-9260-d0622cbe69ad.png)

1.2 Center for World University Rankings (“cwurData.csv”)
As one of the largest and most comprehensive academic ranking of global universities, it was compiled by a Saudi Arabia-based organization since 2012. The dataset, “cwurData.csv”, contains 2200 rows and 14 columns. It will be used to make comparisons with the dataset in 4.1.1 and find any existing bias among ranking systems from different countries. The system uses 6 indicators to rank. Columns found in the dataset are listed below:
![cwur_data](https://user-images.githubusercontent.com/26759376/34130289-1d977174-e3fc-11e7-9659-13f3f0ddec28.png)

### 2. Supplementary Data
2.1 Population Data (“Population Mid-2015.csv”)
The population data is exactly the same dataset we used in the second assignment which contains the populations of a variety of counties collected in mid 2015. This dataset will be used to test the second hypothesis of research question 2. Columns found in the dataset are listed below:
![population_data](https://user-images.githubusercontent.com/26759376/34130353-5682f206-e3fc-11e7-835a-d103b37edcd0.png)

### 3. Data Source Acknowledgement
I got permissions to legally use both university ranking datasets (“timesData.csv” and “cwurData.csv”) in this project from the owners of the Times Higher Education World University Rankings official website and the Center for World University Rankings official website. Data are not allowed to use in a ranking or product that would compete with these ranking systems. If any reviewer wants to reuse these datasets, please acknowledge the ownership with appropriate link back to their official websites as I indicate below.

3.1 Acknowledge the THE ranking dataset (“timesData.csv”)

“timesData.csv” is based on the ranking data provided by the Times Higher Education World University Rankings 

[Link](https://www.timeshighereducation.com/world-university-rankings) to the Times Higher Education World University Ranking official website.

3.2 Acknowledge the CWUR ranking dataset (“cwurData.csv”)

“cwurData.csv” is based on the ranking data provided by the Center for World University Rankings 

[Link](http://cwur.org/) to the Center for World University Rankings official website.

