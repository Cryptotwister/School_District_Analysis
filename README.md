# School_District_Analysis
## Overview of the school district analysis:
We will be helping the chief data scientist for a City School District, Maria with analyzing data on students funding and students standardized test scores. We are given access to every student’s math and reading test scores as well as various information on the schools that they attend. We are given two datasets in CSV format: [school_complete.csv](https://github.com/Cryptotwister/School_District_Analysis/blob/main/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/Cryptotwister/School_District_Analysis/blob/main/Resources/students_complete.csv).
#### Goals
This analysis will assist the School Board and Superintendent in making decisions regarding the school budgets and priorities.
- Our task is to aggregate the data and showcase trends and school performance.
- Additionally, since the school board has notified Maria that the [students_complete.csv](https://github.com/Cryptotwister/School_District_Analysis/blob/main/Resources/students_complete.csv) file shows evidence of academic dishonesty (reading and math grades for Thomas High School ninth graders appear to have been altered.), we need to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once it's done, we need to repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.
## Results:
### District summary
District summary before modifications
![district_summary_df_compromised](https://user-images.githubusercontent.com/42978221/144170990-e845a12d-7e9a-41ec-80a7-ec85c5e32115.png)
District summary after modifications
![district_summary_df_modified](https://user-images.githubusercontent.com/42978221/144171012-728fe9fe-23d5-4329-98c6-05ffe664eecf.png)
After the adjustment 
* Averagage Math Score went down by 0.1
* % Passing Math - down by 0.2
* % Passing reading - down by 0.3
* % Overall Passing - down by 0.1

### School summary

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade

#### Scores by school spending

#### Scores by school size

#### Scores by school type

## Summary:
