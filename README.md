# **School District Analysis**
## **Overview of the School District Analysis**
The purpose of the analysis is to re-analyze the school district's math and reading scores by replacing Thomas High School ninth grader results to NaNs due to evidence of academic dishonesty. 

## **Results:**

The effect of Thomas High School metrics can be summarized as follow when the ninth grader results were replaced with Nans.:

### *District Summary*
1. The district summary results for each category remain intact with no significant changes if the results are evaluated to zero decimal point. 
- District Summary Before Ninth Grade replacement
![District Summary(Before)](https://user-images.githubusercontent.com/70525492/94965927-fa54e900-04c1-11eb-9c80-1d08d1503c88.png)


-  District Summary After Ninth Grade replacement with NaNs
![District Summary(After)](https://user-images.githubusercontent.com/70525492/94961370-21a7b800-04ba-11eb-9165-63bf1ed7f72c.png)

### *School Summary*
1. The school summaries for each school, with the exception of Thomas High School, were not affected with the ninth grader scores were replaced with NaN.

- School summary before replacment
  ![school_summary_before](https://user-images.githubusercontent.com/70525492/94962089-7f88cf80-04bb-11eb-9a22-dfda4331752b.png)

- School summary after replacement where all schools except Thomas High school were not affected. 
  ![school_summary_after](https://user-images.githubusercontent.com/70525492/94962095-81529300-04bb-11eb-8d74-3fae392bbab4.png)

### *Thomas High School Performance*
1. By replacing Thomas High School Ninth Grader results to NaN, the school sees its average math and reading percentage dropped from 93.3% and 97.3% to 66.9% and 69.7% respectively.
2. Should the school board decided to include Thomas High School ninth grade  results into overall passing percentage, it will loose its second place position among all schools. 
- Thomas High School Metrics before ninth grade replacement
  ![THS_before](https://user-images.githubusercontent.com/70525492/94963854-5f0e4480-04be-11eb-8fc2-1e7529d7d3f6.png) 

- Thomas High School Metrics after ninth grade replacement with NaNs
  ![THS_after](https://user-images.githubusercontent.com/70525492/94963861-62093500-04be-11eb-8798-cdd6d02f4117.png)

- Thomas High School Metrics after ninth grade results not included
  ![THS_after_9th_removal](https://user-images.githubusercontent.com/70525492/94964461-78fc5700-04bf-11eb-8835-d4fcce5c8a17.png)

- Thomas High School Top 5 Position before ninth grade replacement
  ![top_5_before_ninth](https://user-images.githubusercontent.com/70525492/94964941-31c29600-04c0-11eb-97da-1143be10dc4b.png)

- Thomas High School Top 5 Position after excluding 9th grade results
  ![top_5_after_ninth](https://user-images.githubusercontent.com/70525492/94964947-338c5980-04c0-11eb-885f-5af2c319c8b4.png)

### *Math and Reading Scores by Grade*
1. Math and Reading Scores before replacing ninth-grader results
![math_score_before](https://user-images.githubusercontent.com/70525492/94967938-a8ae5d80-04c5-11eb-8dcd-176cee11c2de.png)
![reading_score_before](https://user-images.githubusercontent.com/70525492/94967942-aa782100-04c5-11eb-8bed-1b1d0e6fefc4.png)

2. Math and Reading Scores after replacing ninth-grader results with NaN. 
3. The replacment of Thomas High School Ninth-Grader results only affected the Ninth-Graders' results.
![math_score_after](https://user-images.githubusercontent.com/70525492/94968024-c7145900-04c5-11eb-8521-7bdfac14b994.png)
![reading_score_after](https://user-images.githubusercontent.com/70525492/94968030-ca0f4980-04c5-11eb-9e97-b1b0e9a3bd9e.png)

### *Scores by School Spending - No Significant Changes*
1. Scores by School Spending before Ninth-Grader replacement
![school_spending_score_before](https://user-images.githubusercontent.com/70525492/94969136-cb417600-04c7-11eb-8342-898fadc5b321.png)

2. Scores by School Spending after Ninth-Grader replacement
![school_spending_score_after](https://user-images.githubusercontent.com/70525492/94969139-cc72a300-04c7-11eb-84f3-285892b75daf.png)

### *Scores by School Size - No Significant Changes*
1. Scores by school size before Ninth-Grader replacement
![scores_by_school_size_before](https://user-images.githubusercontent.com/70525492/94969748-e6f94c00-04c8-11eb-95bf-d10017b7faa2.png)

2. Scores by school size after Ninth-Grader replacement
  ![scores_by_school_size_after](https://user-images.githubusercontent.com/70525492/94969751-e8c30f80-04c8-11eb-81b4-ed6be1cf2282.png)

### *Scores by School Type - No Significant Changes*
1. Scores by school type before Ninth-Grader replacement
![scores_by_school_type_before](https://user-images.githubusercontent.com/70525492/94970025-6129d080-04c9-11eb-80b8-262e2fb167c4.png)

2. Scores by school type after Ninth-Grader replacement
![scores_by_school_type_after](https://user-images.githubusercontent.com/70525492/94970028-625afd80-04c9-11eb-9c2f-a62a7356d869.png)


## **Summary:**

Based on the final analysis, the four major changes that can be observed in the school district analysis in regards to Thomas High School math and reading results can be summarized as follow:

1. Overall school district summary (all 15 schools) was not affected when Thomas High School ninth grader scores were replaced with NaN. The percentage decrease was 0.3% or less.

2. Signficant dropped in Math and Reading passing percentage when ninth grader percentages were updated to NaN as total students were including the ninth grader for percentage passing calculation.
   - Math passing percentage dropped from 93.3% to 66.9% (-26.4%)
   - Reading passing percentage dropped from 97.3% to 69.7% (-27.6%)
   - Overall math and reading percentage dropped from 90.9% to 65.1% (-25.8%)
   - Lost second position in the top 5 school ranking when ninth grader scores was updated to NaN.
   
3. Significant increased in Math and reading passing percentage when the ninth grader grades were excluded from the percentage passing calculation
   - Math passing percentage increased 66.9% to 93.2% (-0.1% from initial result)
   - Reading passing percentage increased 69.7% to 97.0% (-0.3% from initial result)
   - Overall math and reading percentage increased from 65.1% to 90.6% (-0.3% from initial result)
   - Maintained second position in the top 5 school ranking after the ninth grader grades were excluded from the percentage passing calculation.
   
4. Overall passing scores by school type, school size, and school spending see no significant changes with virtually no difference when evaluated to zero decimal point. 



   

