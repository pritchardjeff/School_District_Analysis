# School_District_Analysis-batman

## Overview of Project

Originally, we were tasked to do data clean up and reporting for the school district. Upon the completion of our original anlaysis, we were told there were issues with one of the schools 9th grade test scores and were asked to nullify their test scores and re run the analysis.


Below, we will walk through the impact of adjusting the scores.

The original script is the file below:

[PyCitySchools.ipynb] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/PyCitySchools.ipynb)

The new script is the file below:

[PyCitySchools_Challenge.ipynb] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/PyCitySchools_Challenge.ipynb)

### Results

- How is the distrcit summary affected?
  - Average Math score went from 79.0 to 78.9
  - Average Reading score stayed the same due to rounding
  - % passing math went down from 75% to 74%
  - % passing reading went down from 86% to 85%
  - % Overall Passing went from 65% to 64%
  - Original:
  ![district_summary_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/district_summary_original.png)
  - New:
  ![district_summary_new] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/district_summary_new.png)
  
- How is the school summary affected?
  - Only school impacted is Thomas High School
  - All fields remained the same other than the average reading score and average math score
  - The average reading score went down from 83.89488% to 83.896082%
  - The average math score went down from 83.41839% to 83.350937%
  - Original:
  ![school_summary_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/school_summary_original.png)
  - New:
  ![school_summary_new] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/school_summary_new.png)

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
  - In terms of % overall passing, Thomas High school went from the 2nd highest performing school to outside the top 5 performing schools.
  - Original:
  ![top_schools_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/top_schools_original.png)
  - New:
  ![top_schools_new.png] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/top_schools_new.png)
  
- How does replacing the ninth-grade scores affect math and reading scores by grade?
  - The only scores impacted were the 9th grade scores at Thomas High School, and the averages were replaced with "nan" values.
  - Original:
  ![schools_by_grade_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/schools_by_grade_original.png)
  - New:
  ![schools_by_grade_new] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/schools_by_grade_new.png)
  
- How does replacing the ninth-grade scores affect scores by school spending?
  - The only spending range impacted is the $630-644 bucket
  - The % Passing Math went from 73% to 67%
  - The % Passing reading went from 84% to 77%
  - The % Overall passing went from 63% to 56%
  - Original:
  ![spending_range_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/spending_range_original.png)
  - New:
  ![spending_range_new] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/spending_range_new.png)
  
- How does replacing the ninth-grade scores affect scores by school size?
  - The only school size impacted was the Medium (1000-2000) bucket
  - The % Passing Math went from 94% to 88%
  - The % Passing Reading went from 97% to 91%
  - The % Overall Passing went from 91% to 85%
  - Original:
  ![school_size_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/school_size_original.png)
  - New:
  ![school_size_new] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/school_size_new.png)
  
- How does replacing the ninth-grade scores affect scores by school type?
  - The Charter schools were the only school type impacted
  - The % Passing Math went from 94% to 80%
  - The % Passing Reading went from 97% to 93%
  - The % Overall Passing went from 90% to 87%
  - Original:
  ![school_type_original] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/school_type_original.png)
  - New:
  ![school_type_new] (https://github.com/pritchardjeff/School_District_Analysis/blob/master/Images/school_type_new.png)
  

### Summary

Overall, the major impact from removing the 9th grade scores from Thomas High School are:
- Thomas High School performace relative to other schools in the district has been overstated
- The performance of schools in the $630-644 spend per student per year bucket was overstated
- The performance of schools in the Medium (1000-2000) size bucket was overstated
- The performance of charter schools was overstated



