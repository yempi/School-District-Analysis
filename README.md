# School-District-Analysis
## Project Overview

The chief data scientist of a school district wants help analyzing student's and school performance to assist the school board to make decisions according to the results of the analysis. Some key information will be obtained from the following points:
- A high-level snapshot of the district's key metrics
- Overview of the key metrics for each school
- Top 5 and bottom 5 performing schools, based on overall passing rate
- Average math score received by students in each grade level at each school
- Average reading score received by students in each grade level at each school
- School perfomance based on:
  - Budget per student
  - School size
  - Type of school 

## Resources
Data source: 
- schools_complete.csv
- students_complete.csv

Software:
- Jupyter Notebook
- Python 3.7.6
- Anaconda 4.11.0

## Results
After a deep dive into all school's performance, the school board notified the chief data scientist of the students_complete.csv file showing evidence of academic dishonesty for reading and math grades for Thomas High School ninth graders. Math and reading scores are being replaced with NaNs to repeat the school district analysis to show possible changes in the overall analysis.

### District Summary
This are the numbers from taking into account all grades of Thomas High School's ninth graders:
<img width="785" alt="Screen Shot 2022-01-30 at 10 38 17 PM" src="https://user-images.githubusercontent.com/83614893/151739715-aa3df4d4-ce8d-44ca-8cd4-a3a8ceee20b7.png">

After replacing this numbers with a NaN value:
<img width="784" alt="Screen Shot 2022-01-30 at 10 36 17 PM" src="https://user-images.githubusercontent.com/83614893/151739551-a4dc1fb2-ac2f-464d-aa00-8f247bf8aa46.png">

- Average math and reading scores remain the same.
- The percentage of students passing math and reading drop 0.1%.
- Overall passing percentage drops 0.3%.

### School Summary
This are the numbers from taking into account all grades of Thomas High School's ninth graders:
<img width="782" alt="after" src="https://user-images.githubusercontent.com/83614893/151740349-bfc39779-b20f-468c-ab24-54a2282c327a.png">

After replacing this numbers with a NaN value:
<img width="781" alt="before" src="https://user-images.githubusercontent.com/83614893/151740339-15204676-4bf3-4f44-9b43-3424b0f60746.png">

- Average math and reading scores drop by 0.1%.
- The percentage of students passing math drops by 0.1%.
- The percentage of students passing reading drops by 0.2%
- Overall passing percentage drop 0.3%.

### Replacing Thomas High School's 9th graders performance 
- Math and reading scores by grade
- Scores by school spending 
- Scores by school size
- Scores by school type

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
