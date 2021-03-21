# School District Analysis

## Overview of the Analysis

The PyCity School Board notified us that there is evidence of academic dishonesty at Thomas High School. It appears that the math and reading grades for the school's 9th grade students have been altered. While the board doesn't know the full extent of it, they have asked us to clean up our [original analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools.ipynb) and present our new findings. To complete this task, we need to re-run our analysis, replacing Thomas High School 9th grader scores with NaN (represents a value that is unpresentable), and compare our findings to our original analysis. This will demonstrate to the board how this unfortunate event affected the overall analysis. 

## Results

### Overview of Results

When we re-ran our analysis for the school board, we needed to replace Thomas High School 9th grader math and reading scores with NaN values. We made this determination because the board agrees that this data is unpresentable (academic dishonesty disqualified it) and we need to keep the 10th through 12th grade data intact. If we replaced those scores with 0 instead of NaN, the 9th grade 0 scores would have greatly skewed the score averages and the percentages of students passing much lower for Thomas High School.

By answering key questions about the data, I will present how my [original analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools.ipynb) compares to our [new analysis](https://github.com/dwwatson1/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb) with 9th grade Thomas High School scores set to NaN.

### How is the district summary affected?
#### Original Analysis
![district_summary_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/district_summary_original.PNG)

#### New Analysis
![district_summary_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/district_summary_new.PNG)

#### Comparison

### How is the school summary affected?
#### Original Analysis
![school_summary_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_summary_original.PNG)

#### New Analysis
![schoool_summary_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/schoool_summary_new.PNG)

#### Comparison

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### Original Analysis
![top_five_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/top_five_original.PNG)

#### New Analysis
![top_five_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/top_five_new.PNG)

#### Comparison

### How does replacing the ninth-grade scores affect math and reading scores by grade?
#### Original Analysis

##### Math  |  Reading
:-------------------------:|:-------------------------:
[math_scores_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/math_scores_original.PNG)  |  ![reading_scores_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/reading_scores_original.PNG)

##### Reading


#### New Analysis

##### Math
![math_scores_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/math_scores_new.PNG)

##### Reading
![reading_scores_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/reading_scores_new.PNG)

#### Comparison

### How does replacing the ninth-grade scores by school spending?
#### Original Analysis
![school_spending_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_spending_original.PNG)

#### New Analysis
![school_spending_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_spending_new.PNG)

#### Comparison

### How does replacing the ninth-grade scores by school size?
#### Original Analysis
![school_size_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_size_original.PNG)

#### New Analysis
![school_size_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_size_new.PNG)

#### Comparison

### How does replacing the ninth-grade scores by school type?
#### Original Analysis
![school_type_original](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_type_original.PNG)

#### New Analysis
![school_type_new](https://github.com/dwwatson1/School_District_Analysis/blob/main/Resources/school_type_new.PNG)

#### Comparison

## Summary of the Analysis

