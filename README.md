# School_District_Analysis
## Overview
In the latest academic review of schools within the district, the school board has determined that the files may have uncovered evidence of academic dishonesty within the district, specifically reading and math grades for ninth-graders attending Thomas High School.  While the extent of academic dishonesty is uncertain, the school board has reached out to Maria, our client, to do a re-analysis of grade reporting within the district, and to replace the suspect grades from Thomas High School with null values.  Maria and the school board will be able to use the new report to better understand the effects of the altered reporting, and then to make more informed decisions on school budgeting and performance within the district.

## Analysis Results
* **District Wide:** There are 461 ninth-graders attending Thomas High School whose math and reading scores were replaced with null values (NaN).  With a total student count near 40,000 district-wide, there were minimal changes to the overall results, generally less than one-percent:

  |  | Original Analysis | Adjusted Analysis |
  | --- | --- | --- |
  | Total Schools | 15 | 15 |
  | Total Students | 39,170 | 38,709 |
  | Total Budget | $24,649,428.00 | $24,649,428.00 |
  | Ave Math Score | 78.99 | 78.93 |
  | Ave Reading Score | 81.88 | 81.86 |
  | % Passing Math | 74.98 | 74.76 |
  | % Passing Reading | 85.81 | 85.66 |
  | % Overall Passing | 65.17 | 64.86 |
* **Thomas High School:** Since all ninth-grade reading and math scores were set to non-numerical values, they could not be used as part of the school averages.  As a result, the new math and reading scores were calculated based upon the tenth--twelfth-grade averages alone,  and reflect only minimal changes overall.  However, the total number of students attending school remains the same and results in a significant negative impact on the passing percentages for Thomas High School in every category.  The adjusted data has major implications on Thomas High School's academic standing within the school district, dropping it from second-highest performing down to eighth amongst the fifteen schools:

  |  | Original Analysis | Adjusted Analysis |
  | --- | --- | --- |
  | Ave Math Score | 83.42 | 83.35 |
  | Ave Reading Score | 83.85 | 83.90 |
  | % Passing Math | 93.27 | 66.91 |
  | % Passing Reading | 97.31 | 69.66 |
  | % Overall Passing | 90.95 | 65.08 |
 * **Math and Reading Scores by Grade:** Only ninth-grade reading and math scores for Thomas High School students were affected, being replaced with null values that could not be used for calculating scores:
 
    | Thomas High School | 9th | 10th | 11th | 12th |
    | --- | --- | --- | --- | --- |
    | Ave Math Score | NaN | 83.09 | 83.50 | 83.50 |
    | Ave Reading Score | NaN | 84.25 | 83.59 | 83.83 |
 * **Scores by School Spending:** Thomas High School spends between $630 and $644 per student, placing it in the third-quartile (large) in spending district wide.  The school budget is $1,043,130.00, and is not affected by variations in academic scores.  As before, the new analysis resulted in minimal changes overall for schools within the same spending range:

    |  | Original Analysis | Adjusted Analysis |
    | --- | --- | --- |
    | Spending Per Student | $630-$644 | $630-$644 |
    | Ave Math Score | 78.52 | 78.50 |
    | Ave Reading Score | 81.62 | 81.64 |
    | % Passing Math | 73.48 | 73.46 |
    | % Passing Reading | 84.39 | 84.32 |
    | % Overall Passing | 62.86 | 62.78 |
  * **Scores by School Size:** Thomas High School has a student population of 1,635, designating it a Medium-size school (1,000-2,000) on a three-tier distric grouping.  No differentiable changes were observed:
    
    |  | Original Analysis | Adjusted Analysis |
    | --- | --- | --- |
    | School Size | Medium | Medium |
    | Ave Math Score | 83.37 | 83.37 |
    | Ave Reading Score | 83.86 | 83.86 |
    | % Passing Math | 93.60 | 93.60 |
    | % Passing Reading | 96.79 | 96.79 |
    | % Overall Passing | 90.62 | 90.62 |
    
* **Scores by School Type:** Thomas High School is listed as a Charter school within the district along with seven other schools.  These school consistently perform better across the board, and generally mediate much of the distrit's overall averages.  Once again, the new analysis resulted in minimal changes for Charter school in the district:

    |  | Original Analysis | Adjusted Analysis |
    | --- | --- | --- |
    | School Type | Charter | Charter |
    | Ave Math Score | 83.47 | 83.47 |
    | Ave Reading Score | 83.90 | 83.90 |
    | % Passing Math | 93.62 | 93.61 |
    | % Passing Reading | 96.59 | 96.55 |
    | % Overall Passing | 90.43 | 90.39 |

 
