# University Rankings Analysis
This is an exploratory analysis of bias in global university rankings by the Academic Ranking of World Universities, Center For World University Rankings, and the Times Higher Education World University Rankings.

## Data Sources
### Academic Ranking of World Universities 2005 - 2015
- Owner: ShanghaiRanking Consultancy is a fully independent organization dedicating to research on higher education intelligence and consultation.
- Trustworthiness: Trustworthy; Transparent, replicable methodology
- Type: External data
- Collection Method: Quantitative performance statistics for each university, including the quality of education, quality of faculty, research output, and per capita performance, are automatically collected.
- Collection Type: Administrative data
- Collection System: Automatic collection
- Time Lag: Yes; The available dataset contains the data from 2005 through 2015; Performance statistics use weighted averages from previous years up to 100 years.
- Data Description: The data includes ARWU world ranking information, university information, ARWU category rankings, and the ARWU score.
- Justification: This data set provides a world university ranking developed by an organization located in the East Asia for comparison to organizations located in the West and Middle East. This dataset has a transparent and replicable methodology.
- Limitations: The methodology uses cumulative data from past years to calculate a current rank. Using older data could create a time lag issue, however ARWU uses weighted averages and the use of multiple past years would have a stabilizing effect versus only using the previous year which would be more susceptible to world events like the recent covid pandemic. Errors are unlikely due to the automated nature of the collection process and transparent methodology.
- Bias: Possible bias toward universities in the company’s own country, China. ARWU provides information on their methodology to allow replication and peer review.

### Center For World University Rankings 2012-2015
- Owner: The Center for World University Rankings (CWUR) is a leading consulting organization providing policy advice, strategic insights, and consulting services to governments and universities to improve educational and research outcomes.
- Trustworthiness: Trustworthy; Transparent, replicable methodology
- Type: External data
- Collection Method: Quantitative performance statistics for each university, including the quality of education, employability, quality of faculty, and research, are automatically collected.
- Collection Type: Administrative data
- Collection System: Automatic collection
- Time Lag: Yes; The available dataset contains the data from 2012 through 2015; Performance statistics use weighted averages from recent previous years, most are from 2 through 11 of the years previous to the ranking list’s year.
- Data Description: The data includes CWUR world ranking information, university information, CWUR category rankings, and the CWUR score.
- Justification: This data set provides a world university ranking developed by an organization located in the Middle East for comparison to organizations located in the West and East Asia. This dataset has a transparent and replicable methodology.
- Limitations: The methodology uses cumulative data from the past 11 years to calculate a current rank. Using older data could create a time lag issue, however CWUR uses weighted averages and the use of multiple past years would have a stabilizing effect versus only using the previous year which would be more susceptible to world events like the recent covid pandemic. Errors are unlikely due to the automated nature of the collection process and transparent methodology.
- Bias: Possible bias toward universities in the company’s own country, United Arab Emirates. CWUR provides information on their methodology to allow replication and peer review.

### Times Higher Education World University Rankings 2011-2016
- Owner: Times Higher Education (THE), is a British magazine reporting specifically on news and issues related to higher education.
- Trustworthiness: Trustworthy; Transparent, replicable methodology
- Type: External data
- Collection Method: Quantitative performance statistics for each university, including the quality of education, employability, quality of faculty, and research, are automatically collected. Uses the WUR 3.0 methodology, which includes 18 calibrated performance indicators that measure an institution’s performance across five areas: teaching, research environment, research quality, industry, and international outlook utilizing a mix of manual and automatic collection methods.
- Collection Type: Administrative data
- Collection System: Automatic and manual collection
- Time Lag: Yes; The available dataset contains the data from 2011 through 2016; Performance statistics use weighted averages from recent previous years.
- Data Description: The data includes THE world ranking information, university information, THE category scores, and the THE score.
- Justification: This data set provides a world university ranking developed by an organization located in the West for comparison to organizations located in the Middle East and East Asia. This dataset has a transparent methodology.
- Limitations: The methodology uses cumulative data from past years to calculate a current rank. Using older data could create a time lag issue, however THE uses weighted averages and the use of multiple past years would have a stabilizing effect versus only using the previous year which would be more susceptible to world events like the recent covid pandemic. The methodology uses survey data which may include manual collection errors. THE has taken measures to balance the magnitude difference of responses between different surveys and universities.
- Bias: Possible bias toward universities in the company’s own country, the United Kingdom.

## Research Questions
- What countries have the most ranked universities?
- Are the rankings drastically different between datasets?
- How do rankings evolve over time?
- What factors do these institutions value?
- How do their testing methods differ from each other?
- What countries and general regions have growth or decline in their number of universities over time?
- What do world rankings look like after combining the rankings from all three datasets?
- Which dataset is the closest to this combined ranking?
- Which variable rankings most closely resembled their datasets’ world rankings?
- What does a heat map of universities by country look like?
- What countries are trending up or down over time?
- What are the greatest rank increases and decreases over a year? 5 years? 10 years?

## Cleaning Procedures
### Academic Ranking of World Universities 2005 - 2015
- national_rank: 1 null value; no changes
- total_score: 3796 null values; no changes
- alumni: 1 null values; no changes
- award: 2 null values; no changes
- hici: 2 null values; no changes
- ns: 22 null values; no changes
- pub: 2 null values; no changes
- pcp: 2 null values; no changes

### Center For World University Rankings 2012-2015
- broad_impact: 200 null value; no changes

### Times Higher Education World University Rankings 2011-2016
- num_students: 59 null value; no changes
- student_staff_ratio: 59 null values; no changes
- international_students: 67 null values; no changes
- female_male_ratio: 233 null values; no changes

## Supporting Documentation
- [Final Tableau Public Presentation](https://public.tableau.com/app/profile/bert.pearce/viz/UniversityRankings_17233233461230/Storyboard?publish=yes)
- [World University Rankings - Kaggle](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings)
- [Academic Ranking of World Universities 2005-2015 Data](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings/data?select=shanghaiData.csv)
- [Center For World University Rankings 2012-2015 Data](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings/data?select=cwurData.csv)
- [Times Higher Education World University Rankings 2011-2016 Data](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings/data?select=timesData.csv)
- [Academic Ranking of World Universities](https://www.shanghairanking.com/rankings)
- [Center For World University Rankings](https://cwur.org)
- [Times Higher Education World University Rankings](https://www.timeshighereducation.com/world-university-rankings)
