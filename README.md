# School_District_Analysis
## Overview
In the latest academic review of schools within the district, the school board has determined that the files may have uncovered evidence of academic dishonesty within the district, specifically reading and math grades for ninth-graders attending Thomas High School.  While the extent of academic dishonesty is uncertain, the school board has reached out to Maria, our client, to do a re-analysis of grade reporting within the district, and to replace the suspect grades from Thomas High School with null values.  Maria and the school board will be able to use the new report to better understand the effects of the altered reporting, and then to make more informed decisions on school budgeting and performance within the district.

## Analysis Results
* **District Wide:** There are 461 ninth-graders attending Thomas High School whose math and reading scores were replaced with null values (NaN).  With a total student count near 40,000 district-wide, there were nominal changes to the overall results, generally less than one-percent

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
* **Thomas High School:** Since all ninth-grade reading and math scores were set to non-numerical values, they could not be used as part of the school averages.  As a result, the new math and reading scores were cacluated based upon the tenth--twelvth-grade averages alone, and reflect only minimal changes overall.  However, the total number of students attending school remains the same and results in a significant negative impact on the passing percentages for Thomas High School in every category.
  |  | Original Analysis | Adjusted Analysis |
  | --- | --- | --- |
  | Ave Math Score | 83.42 | 83.35 |
  | Ave Reading Score | 83.85 | 83.90 |
  | % Passing Math | 93.27 | 66.91 |
  | % Passing Reading | 97.31 | 69.66 |
  | % Overall Passing | 90.95 | 65.08 |
