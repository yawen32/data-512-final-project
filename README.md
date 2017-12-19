# DATA 512 Final Project Report: Analysis of World University Rankings
## Abstract
The purpose of this project is to perform an exploratory analysis on rankings of global universities that can provide applicants a guideline in many different aspects to help them make better decisions on their applications. The project also strives to suggest improvements in the areas covered by the ranking systems to make them stronger. However, often ranking a university is a difficult and controversial practice due to many influences, including geographical coverage, institutional coverage, the way indicators are calculated, etc. Thus, biases caused by such factors are taken into consideration. Two global university ranking datasets which producers are from very different places are used to find out underlying biases among different ranking systems. 

Overall, citation scores have relatively obvious impacts on rankings. On the contrary, student staff ratio didn’t show a clear correlation with rankings. High ranked universities are more likely from developed countries. However, population is not a significant contributor to rankings. We also found bias does exist among different ranking systems.

## Data
### 1. University Ranking Data

1.1 Times Higher Education World University Ranking (“timesData.csv”)
Times Higher Education is a well-known global university ranking system which mainly focuses on a lot of non-English educational institutions and their commercialization. It collaborated with Thomson Reuters and started to use its own methodology since 2011. The dataset, “timesData.csv”, contains 2603 rows and 14 columns (13 performance indicators and 1 column for year). The performance indicators cover 5 major fields: teaching, research, citations, income, international outlook. This dataset is used as a prime dataset to answer the majority of research questions. Columns found in the dataset are listed below:
![the_data](https://user-images.githubusercontent.com/26759376/34130268-0dc77d0c-e3fc-11e7-9260-d0622cbe69ad.png)

1.2 Center for World University Rankings (“cwurData.csv”)
As one of the largest and most comprehensive academic ranking of global universities, it was compiled by a Saudi Arabia-based organization since 2012. The dataset, “cwurData.csv”, contains 2200 rows and 14 columns. It is used to make comparisons with the dataset in 4.1.1 and find any existing bias among ranking systems from different countries. The system uses 6 indicators to rank. Columns found in the dataset are listed below:
![cwur_data](https://user-images.githubusercontent.com/26759376/34130289-1d977174-e3fc-11e7-9659-13f3f0ddec28.png)


**Both ranking datasets can be downloaded from Kaggle website.**

[Link](https://www.kaggle.com/mylesoneill/world-university-rankings/data) to download raw data.

Kaggle [Privacy Policy](https://www.kaggle.com/about/privacy) and [Terms of Use](https://www.kaggle.com/terms)

### 2. Supplementary Data
2.1 Population Data (“Population Mid-2015.csv”)
The population data is exactly the same dataset we used in the second assignment which contains the populations of a variety of counties collected in mid 2015. This dataset is used to test the second hypothesis of research question 2. Columns found in the dataset are listed below:
![population_data](https://user-images.githubusercontent.com/26759376/34130353-5682f206-e3fc-11e7-835a-d103b37edcd0.png)

Check the data on [Population Research Bureau website](http://www.prb.org/DataFinder/Topic/Rankings.aspx?ind=14)

Download [here](http://www.prb.org/RawData.axd?ind=14&fmt=14&tf=76&loc=34235%2c249%2c250%2c251%2c252%2c253%2c254%2c34227%2c255%2c257%2c258%2c259%2c260%2c261%2c262%2c263%2c264%2c265%2c266%2c267%2c268%2c269%2c270%2c271%2c272%2c274%2c275%2c276%2c277%2c278%2c279%2c280%2c281%2c282%2c283%2c284%2c285%2c286%2c287%2c288%2c289%2c290%2c291%2c292%2c294%2c295%2c296%2c297%2c298%2c299%2c300%2c301%2c302%2c304%2c305%2c306%2c307%2c308%2c311%2c312%2c315%2c316%2c317%2c318%2c319%2c320%2c321%2c322%2c324%2c325%2c326%2c327%2c328%2c34234%2c329%2c330%2c331%2c332%2c333%2c334%2c336%2c337%2c338%2c339%2c340%2c342%2c343%2c344%2c345%2c346%2c347%2c348%2c349%2c350%2c351%2c352%2c353%2c354%2c358%2c359%2c360%2c361%2c362%2c363%2c364%2c365%2c366%2c367%2c368%2c369%2c370%2c371%2c372%2c373%2c374%2c375%2c377%2c378%2c379%2c380%2c381%2c382%2c383%2c384%2c385%2c386%2c387%2c388%2c389%2c390%2c392%2c393%2c394%2c395%2c396%2c397%2c398%2c399%2c400%2c401%2c402%2c404%2c405%2c406%2c407%2c408%2c409%2c410%2c411%2c415%2c416%2c417%2c418%2c419%2c420%2c421%2c422%2c423%2c424%2c425%2c427%2c428%2c429%2c430%2c431%2c432%2c433%2c434%2c435%2c437%2c438%2c439%2c440%2c441%2c442%2c443%2c444%2c445%2c446%2c448%2c449%2c450%2c451%2c452%2c453%2c454%2c455%2c456%2c457%2c458%2c459%2c460%2c461%2c462%2c464%2c465%2c466%2c467%2c468%2c469%2c470%2c471%2c472%2c473%2c474%2c475%2c476%2c477%2c478%2c479%2c480) as a CSV file named `Population Mid-2015.csv`

### 3. Data Source Acknowledgement
I got permissions to legally use both university ranking datasets (“timesData.csv” and “cwurData.csv”) in this project from the owners of the Times Higher Education World University Rankings official website and the Center for World University Rankings official website. Data are not allowed to use in a ranking or product that would compete with these ranking systems. If any reviewer wants to reuse these datasets, please acknowledge the ownership with appropriate link back to their official websites as I indicate below.

3.1 Acknowledge the THE ranking dataset (“timesData.csv”)

“timesData.csv” is based on the ranking data provided by the Times Higher Education World University Rankings 

[Link](https://www.timeshighereducation.com/world-university-rankings) to the Times Higher Education World University Ranking official website.

3.2 Acknowledge the CWUR ranking dataset (“cwurData.csv”)

“cwurData.csv” is based on the ranking data provided by the Center for World University Rankings 

[Link](http://cwur.org/) to the Center for World University Rankings official website.

