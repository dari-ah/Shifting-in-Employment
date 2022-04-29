# Employment Analysis (2018-2021)
  In this project, I analyzed the changes in employment, such as total positions and wages in the 2018-2021 period. I was especially interested in how COVID-19 could impact the job market. I calculated the differences in wages and employment to determine the potential shiftings.

### Table of Contents
* [Objective](#objective)
* [Dataset](#dataset)
* [Results](#results)

## Ojective:
  During the pandemic, many companies had to reduce their employment and wages. Consequently, I wanted to inspect the employment differences before and after the pandemic to examine potential significant impacts. Additionally, I wanted to investigate the ranking of jobs based on wage differences throughout the year. My goal was to find the most change resistance jobs. Finally, I aimed to determine jobs that have the highest increase and decrease in wages.

## The Dataset:
  The dataset I used for this project is the [Occupational Employment and Wage Statistics (OEWS)](https://www.bls.gov/data/#employment), provided by the U.S Bureau of Labor. I considered the data from 2018 to 2021 since this time frame included employment information before and after the pandemic. The given data set was organized by year with similar information for each year. However, the data does not include the same group of jobs every year. Additionally, the data contains some duplicates that can cause complications for querying. 
  Before starting, I created a [data schema model](https://github.com/dari-ah/Shifting-in-Employment/blob/cc36a2aedf9582ec64482ba1f9f85c948cce61b3/Data%20Schema-employment.pdf) as attached and organized the data accordingly. Since there were many duplicate items in the primary key column, I removed the duplicates and changed some indexes to make them unique. Additionally, the original dataset includes the total employment for each year. I separated this information into a different table for reference since I wanted to perform my calculation.
  
## Results: 
  The job that increased the most in employment is Healthcare Support Occupations. On the other hand, the job that decreased the most is Other Personal Care and Service Workers. The two occupations seemed to be correspondent to the COVID-19 outbreak. During the pandemic, health care workers were in extreme demand as hospitalized patients skyrocketed. Additionally, mandatory quarantine followed right after, putting restrictions upon closed contact services.  
   One interesting finding I made was that jobs with the highest wage increase and jobs with the highest wage decrease both belonged in the same industry. Oral and Maxillofacial Surgeons saw the highest increase of $234990 in average annual wage. Meanwhile, Prosthodontists saw the highest decrease of $71140 in average annual wage. 
   The highest-paying jobs were Anesthesiologists (for 2018-2020) and Cardiologists (for 2021), which were all in the medical sector. Concurrently, the lowest paying jobs were Combined Food Preparation and Serving Workers (Including Fast Food) (for 2018), Shampooers (for 2019 and 2021), and Cooks (Fast Food) (for 2020). These jobs were in the minimum wage, customer service sector.
  
  [View my visualization](https://app.powerbi.com/groups/me/dashboards/a194e4c2-7d92-4d38-89ae-7248e5327c8b?redirectedFromSignup=1)
  
  From my analysis, jobs that were the most resistant to changes were jobs in healthcare services. 
