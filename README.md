# Careers in Data and It's Future

## INTRODUCTION

As a Master's student in Analytics, this case study offers a valuable opportunity to apply my academic learnings to real-world data, providing insights into the diverse landscape of job roles within the data domain. The dataset presents an in-depth look at various positions, salaries, and other job-related statistics that are essential for understanding current trends in the data job market.

This analysis is not just an academic exercise; it's a pivotal exploration that informs future professionals—like myself—about the industry's direction, the value of different roles, and the competitive landscape of salaries and job settings. Given the dynamic nature of the data field, with its evolving technologies and methodologies, this case study stands as a crucial reference for students to align their educational paths with market demands.

## THE WORKFLOW
Prior to working on the data set, I decided to follow a data workflow system to help me keep track and understand of what I was doing and trying to achieve. The steps are as follows.

Business questions - Objective
Data sourcing and Loading
Data Cleaning
Descriptive Statistics - Exploratory Data Analysis
Data Analysis of Main attributes
Key Findings

## OBJECTIVE OF THE CASE STUDY
The objective of this case study is to understand the salary dynamics within the data analysis field, particularly how various factors such as job category, experience level, company location, size, and work setting influence compensation for entry-level positions.

This case study is useful because it provides actionable insights for both job seekers and employers in the data analysis sector. For job seekers, especially those at the entry level, it highlights where and under what conditions they might find the most lucrative opportunities. For employers, it offers a benchmark to ensure competitive salary offerings and understand how different factors contribute to salary expectations, aiding in strategic hiring and retention practices.

## DATA SOURCING
The data is located at ai-jobs.net and entitled "The Global AI, ML, Data Science Salary Index for 2023" which is based on internal data survey submissions and jobs with open salaries, as the authors describe the data. The data is processed and updated every week. You can contribute to them by submitting your salary info.


I have downloaded the data set from Murilo Zangari profile in Kaggle, where you can find the data card, the Metadata, and the License.This case study was also inspired by his attempt on the data set.

The data set contains the following variables
*work_year - The year in which the data was collected.
*job_title - The precise job title, such as 'Data Scientist', 'Data Engineer', or 'Data Analyst'.
*job_category - A classification of job roles into broader categories to facilitate analysis.
*salary_currency - The currency in which the salary is paid, for example, US dollars or euros.
*salary - The annual gross compensation for the position in local currency.
*salary_in_usd - The annual gross salary in US dollars (USD). This standard currency translation helps with global wage comparisons and studies.
*employee_residence - The nation of residence of the employee.
*experience_level - Determines the employee's professional experience level. Some common categories include 'Entry-level', 'Mid-level', 'Senior', and 'Executive'.
*employment_type - Indicates the type of employment, such as 'full-time', 'part-time', or 'contract'.
*work_setting - The work location or environment, such as 'Remote', 'In-person', or 'Hybrid'.
*company_location - The country where the company is based.
*company_size - The employer's company size, which is often classified as small (S), medium (M), or big (L).

### EXPLORATORY DATA ANALYSIS

### DESCRIPTIVE STATISTICS

The summary of the data set.
1. Time Frame: The dataset spans from 2020 to 2023, focusing on recent job data.
2. Entries: Consists of 9,355 job entries, indicating a comprehensive dataset with no missing values in categorical fields.
3. Categorical Data: Includes job titles, job categories, salary currencies, employee residences, experience levels, employment types, work settings, company locations, and company sizes, all as character types.
4. Salary Range: Salaries in local currency range from  
14
,
000
t
o
 450,000, with similar figures in USD, suggesting a wide variation in compensation across different jobs.
5. Central Tendency: The average salary is slightly higher than the median, hinting at a distribution skewed by higher salaries.
6. Distribution: The first and third quartiles of salaries indicate that the middle 50% of the data is well-distributed, with half of the salaries falling within a specific central range.

## ANALYSIS OF KEY DETERMINANTS

### 1. Heatmap of Average salary grouped by job category and experience level



   ![Heatmap](https://github.com/Rach-Maguluri/Careers-in-Data-and-its-Future-/blob/main/dc1.png)



  *Salaries generally increase with experience across data-related job categories.
  *An exception is observed in 'Data Analysis', where senior roles have lower average salaries than executive positions.
  *'Data Science and Research' offers the highest entry-level salaries, significantly higher than those in 'Data Analysis'.
  *The top salaries are found in executive roles within 'Machine Learning AI' and 'Data Science and Research'.
  *These findings highlight the value of experience, specialization, and market demand within the data profession.

### 2. Entry-level Data Analysis & Exploration


   
   ![Exploration](https://github.com/Rach-Maguluri/Careers-in-Data-and-its-Future-/blob/main/dc2.png)




### 3. The Entry Level Data Analysis Average salaries grouped by Company Location



   ![CompanyLocation](https://github.com/Rach-Maguluri/Careers-in-Data-and-its-Future-/blob/main/dc3.png)



   *Entry-level Data Analysis salaries are highest in the United States, averaging $77,000, leading other countries.
   *Luxembourg and the United Kingdom follow, with average salaries of $59,000 and $58,000, respectively.
   *Germany ranks fourth, with an average entry-level salary of $54,000.
   *The sample sizes vary significantly: 103 entries from the United States, 10 from the United Kingdom, 2 from Germany, and 1 from Luxembourg.
   *The robustness of conclusions may be affected by the sample size, and findings could change with future data updates and larger samples.




### 4. Trend of Average Salaries for entry level data analysts


   
   ![EntryLevel](https://github.com/Rach-Maguluri/Careers-in-Data-and-its-Future-/blob/main/dc4.png)




   *Company size influences average salaries, with 'medium' and 'large' companies generally providing higher pay than smaller ones.

   *Interestingly, medium-sized companies tend to offer higher average salaries compared to large companies. However, this analysis doesn't account for variables like company location. For instance, the United States, which boasts the highest overall average salary, predominantly features medium-sized companies in the dataset.




### 5. Entry Level Analysis Salaries grouped by Work Setting



   
   ![Worksetting](https://github.com/Rach-Maguluri/Careers-in-Data-and-its-Future-/blob/main/dc5.png)
   



### 6. Average Salary of Data Analysis Category grouped by experience level, company size and work setting.
   
    
   ![Combined](https://github.com/Rach-Maguluri/Careers-in-Data-and-its-Future-/blob/main/dc6.png)
   

 
   The heat map analysis yields the following insights:

   *Entry-level employees at small companies with hybrid work arrangements tend to have the lowest average salaries. Conversely, entry-level staff at medium-sized companies working on-site command the highest average salaries, reaching $82k for such positions.

   *Senior Data Analysts employed full-time at large companies receive the top average salaries.

   *The predominant determinant of average salary in the US appears to be the employee's experience level.


   

## KEY FINDINGS


1. Experience level significantly impacts salary, with "Machine Learning and AI" roles showing a rise from $93 k for entry level to $207k for executive positions.
2. Top paying fields include 'Machine Learning and AI', 'Data Science and Research', 'Data Engineering', and 'Leadership and Management'.
3.'BI and Visualization' offers higher average salaries compared to 'Data Analysis', despite similar skill sets.
4. The US, UK, and Germany are top-paying countries for entry-level Data Analysts, with average salaries of $77k, $58k and $57k respectively, not accounting for living costs.
5. Work setting (in-person vs. remote) shows minimal impact on salaries, with entry-level positions averaging around $72k - $73k.


The fields of "Data Science and Research" and "Machine Learning and AI" emerge as attractive career choices, offering not only competitive salaries from the outset but also a path rich in opportunities for advancement and job satisfaction, given their growing demand and developmental prospects.



## Future Considerations:

1. Cost of Living Adjustment: Introducing a cost of living column for each country can provide a more nuanced view, allowing for a comparison of salaries against local living expenses to identify the most economically advantageous locations for data analysts.

2. Enhancing Data Diversity: Addressing data imbalances by augmenting the dataset with more entries from less represented categories can offer a more comprehensive analysis. Promoting wider survey participation among data professionals across different specialties could diversify the data.

3. Tracking Industry Trends: Regular analysis updates, aligned with the dataset's weekly refreshes, can capture evolving industry trends. By consistently integrating new data and revisiting previous findings, a dynamic and up-to-date overview of the data job market can be maintained.


 
