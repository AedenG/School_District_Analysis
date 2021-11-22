# School_District_Analysis

## Project Overview
Initially I was asked to analyze student funding and standardized test score data to help inform decision making at school and district levels. The school board has become aware that there is evidence of academic dishonesty in the data reported by Thomas High School for ninth graders. I have been tasked with replacing the math and reading scores with NANs while keeping the rest of the data intact. They would like the school district analysis to be repeated.

## Resources
- Data Source: schools_complete.csv, students_complete.csv

## Results
### District Summary
Compared to the initial district summary, I found the following:
-	The average math score reduced from 79 to 78.9.
-	The average reading score reduced from 81.9 to 78.9.
-	The percent of students passing math reduced from 75% to 74.8%.
-	The percent of students passing reading reduced from 86% to 85.7%.
-	The overall percent of students passing both math and reading reduced from 65% to 64.9%.

9th Grade Scores Replaced with NaN:

<img width="628" alt="ths_nan" src="https://user-images.githubusercontent.com/91852495/142791830-be55e02b-8fb5-481f-ac99-fa20a27278f4.png">

Initial District Summary:

<img width="615" alt="district_summary_old" src="https://user-images.githubusercontent.com/91852495/142791953-85cc6812-c69d-42d2-b3ae-b387cc6266c7.png">

District Summary with Thomas High School 9th Grade Scores Replaced:

<img width="941" alt="District_summary_df_new" src="https://user-images.githubusercontent.com/91852495/142791291-616494ac-ef55-420e-a06c-6f83d202cd57.png">


### School Summary
Compared to the initial school summary, I found the following changes for Thomas High School:
-	The percent of students passing math increased from 66.911315% to 93.185690%.
-	The percent of students passing reading increased from 69.663609% to 97.018739%.
-	The percent of students passing math and reading increased from 65.076453% to 90.630324%.

Thomas High School in School Summary Before Replaced Values:
<img width="998" alt="ths_before_replace" src="https://user-images.githubusercontent.com/91852495/142792141-0f42f019-811a-45e2-9eb9-fff719ef2eb7.png">

Thomas High School in School Summary After Replaced Values:
<img width="973" alt="ths_after_replace" src="https://user-images.githubusercontent.com/91852495/142792178-bd5832fb-1f54-46ba-bf0b-fcd78fc73d9c.png">

### Thomas High School’s Performance 
- Replacing the data for ninth graders does not affect the standing of Thomas High School compared to other schools in terms of rank. Despite the reduction in overall passing percentage in the second school district analysis, Thomas High School is still ranked as the # 2 performing school in the district. 

Top Five Schools:
<img width="991" alt="Top_5" src="https://user-images.githubusercontent.com/91852495/142792498-ab9825eb-463a-4a9a-ba47-6de6914afbe8.png">

Bottom Five Schools:
<img width="980" alt="Bottom_5" src="https://user-images.githubusercontent.com/91852495/142792524-0e091e4b-28a7-4192-afb8-07ed75052cd6.png">

### School Metrics
- Math and Reading Scores by Grade
  -	There are no changes to the 10th-12th grade math and reading scores
  -	9th grade math and reading scores for Thomas High School have a value of NaN

  - Math Scores by Grade:
<img width="310" alt="math_by_grade" src="https://user-images.githubusercontent.com/91852495/142792715-bb478ce0-1228-49fa-a8ca-4f7248662d69.png">
  
  - Reading Scores by Grade:
<img width="307" alt="reading_by_grade" src="https://user-images.githubusercontent.com/91852495/142792789-8d016d22-06ab-423b-b7e1-3070455538b3.png">

- Scores by School Spending
  - Scores have such a minimal difference in the $630-644 bin, to which Thomas High School belongs, that there is a negligible change noted after rounding. 

  - School Spending per Student:<br/>
<img width="831" alt="Spending_ranges_new" src="https://user-images.githubusercontent.com/91852495/142792953-781be96c-cf90-463a-b3b9-985c0744d4e0.png">

- Scores by School Size
  -	Thomas High School has 1635 students. Scores have such a minimal difference in the Medium (1000-2000) school size bin that there is a negligible change noted after rounding. 

  - Subject Scores by School Size:<br/>
<img width="766" alt="School_size_new" src="https://user-images.githubusercontent.com/91852495/142793036-eb7d3a36-2a08-4514-8735-dcd189781423.png">


- Scores by School Type
  -	Thomas High School is a charter school. Scores have such a minimal difference in the charter school type category that there is a negligible change noted after rounding. 

  - Subject Scores by School Type:<br/>
<img width="712" alt="School_type_new" src="https://user-images.githubusercontent.com/91852495/142793134-ddadde20-b977-4be6-b6a5-025be38f473d.png">

## Summary 
Math and reading scores, and the percentage of students passing math, reading, and both subjects, have slightly reduced for the school district when removing 9th grade scores from Thomas High School’s data. In the school summary, we can see that for Thomas High School, the percentage of students passing math, reading, and both subjects has increased after removing 9th grade data. There are very minimal but negligible changes to school spending per student bin $630-644, medium school size, and charter school type categories. Replacing the ninth grade data for math and reading does not affect Thomas High School's rank.
