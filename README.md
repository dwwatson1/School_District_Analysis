# PyCity School District Analysis

## Overview of the Analysis
The PyCity School Board notified us that there is evidence of academic dishonesty at Thomas High School. It appears that the math and reading grades for the school's 9th-grade students have been altered. While the board doesn't know the full extent of it, they have asked us to clean up our [original analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools.ipynb) and present our new findings. To complete this task, we need to re-run our analysis, replacing Thomas High School's 9th grader scores with NaN (which represents a value that is unpresentable), and compare our findings to our original analysis. This will demonstrate to the board how this unfortunate event affected the overall analysis. 

## Results of the Analysis

### Analysis Resources
* Data Sources: [schools_complete](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/schools_complete.csv), [students_complete](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/students_complete.csv), and [clean_students_complete](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/clean_students_complete.csv)
* Software: Jupyter Notebook 6.1.4 
* Notebooks: [original analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools.ipynb) & [new analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)
 
### Overview of Results
When we re-ran our analysis for the school board, we needed to replace Thomas High School's 9th grader math and reading scores with NaN values. We made this determination because the board agrees that this data is unpresentable (academic dishonesty disqualified it) and we need to keep the 10th through 12th-grade data intact. If we replaced those scores with 0 instead of NaN, the 9th grade 0 scores would have greatly skewed the score averages and the percentages of students passing much lower for Thomas High School.

By answering key questions about the data, I will present how my [original analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools.ipynb) compares to our [new analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb) with 9th grade Thomas High School scores set to NaN.  

### How is the district summary affected?or
#### Original Analysis
![district_summary_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/district_summary_original.PNG)

#### New Analysis
![district_summary_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/district_summary_new.PNG)

#### Comparison
The district summary comparison shows that the metrics hardly changed when the scores were replaced. **% Passing Math** dropped by **0.2%**, **% Passing Reading** dropped by **0.1%**, and **% Overall Passing** dropped by **0.3%**. 

### How is the school summary affected?
#### Original Analysis
![school_summary_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_summary_original.PNG)

#### New Analysis
![schoool_summary_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/schoool_summary_new.PNG)

#### Comparison
The school summary comparison demonstrates that Thomas High School was the only school with metrics affected by the score replacement. However, the minor changes in **Average Math Score**, **Average Reading Score**, **% Passing Math**, **% Passing Reading**, and **% Overall Passing** were **>0.10** for average grades categories **>0.35** for % passing categories. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### Original Analysis
![top_five_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/top_five_original.PNG)

#### New Analysis
![top_five_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/top_five_new.PNG)

#### Comparison
The top five ranked performing schools (highest % overall passing) in the district remained unchanged after replacing Thomas High School scores and running the new analysis. The school retained its second-place position in the district.

### How does replacing the ninth-grade scores affect math and reading scores by grade?
#### Original Analysis - Math and Reading

![math_scores_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/math_scores_original.PNG)    ![reading_scores_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/reading_scores_original.PNG)

#### New Analysis - Math and Reading

![math_scores_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/math_scores_new.PNG)    ![reading_scores_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/reading_scores_new.PNG)

#### Comparison
The comparison above shows that the average math score of **83.6** and the average reading score of  **83.7** for Thomas High School 9th graders were affected and replaced with NaN. No other scores were affected.

### How does replacing the ninth-grade scores by school spending?
#### Original Analysis
![school_spending_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_spending_original.PNG)

#### New Analysis
![school_spending_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_spending_new.PNG)

#### Comparison
The school spending comparison demonstrates that the **Average Math Score**, **Average Reading Score**, **% Passing Math**, **% Passing Reading**, and **% Overall Passing** remained unchanged from the original to the new analysis.

### How does replacing the ninth-grade scores by school size?
#### Original Analysis
![school_size_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_size_original.PNG)

#### New Analysis
![school_size_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_size_new.PNG)

#### Comparison
The school size comparison shows that the **Average Math Score**, **Average Reading Score**, **% Passing Math**, **% Passing Reading**, and **% Overall Passing** remained unchanged from the original to the new analysis.

### How does replacing the ninth-grade scores by school type?
#### Original Analysis
![school_type_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_type_original.PNG)

#### New Analysis
![school_type_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_type_new.PNG)

#### Comparison
The school size comparison demonstrates that the **Average Math Score**, **Average Reading Score**, **% Passing Math**, **% Passing Reading**, and **% Overall Passing** remained unchanged from the original to the new analysis.

## Summary of the Analysis
### Overview
By answering these key questions above, we found that there were a few differences in Thomas High School metrics, albeit very minor, after we ran the new analysis. Those differences from the original to the new analysis are listed below.

### Thomas High School Metrics Differences
* **Average Math Score**
  * 83.42 to 83.35 (lowered by 0.07)
* **Average Reading Score**
  * 83.85 to 83.90 (increased by 0.05)
* **% Passing Math**
  * 93.27 to 93.19 (lowered by 0.08)
* **% Passing Reading**
  * 97.31 to 97.02 (lowered by 0.29%)
* **% Overall Passing**
  * 90.95 to 90.63 (lowered by 0.32)

### Important Things to Note
Had we not assigned Thomas High School 9th graders scores as NaN and not replaced **% Passing Math**, **% Passing Reading**, and **% Overall Passing** values, the school summary for Thomas High School would have looked like the following:

![school_summary_no_replace](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_summary_no_replace.PNG)

As you can see from the image above, if we hadn't kept the data intact after replacing 9th-grade scores, like we were asked to by the school board, Thomas High School's district ranking would've declined well below the top 5 (Pena High School is #5 with an % overall passing of 90.54). The **% Passing Math**, **% Passing Reading**, and **% Overall Passing** values were 66.91%, 69.66%, and 65.07%, respectively. The steps we took in our new analysis, with the school board's guidance, prevented a localized occurrence of academic dishonesty from being detrimental to Thomas High School's reputation and standing among PyCity District Schools.     
