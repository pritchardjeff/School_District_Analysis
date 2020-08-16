# School_District_Analysis

## Overview of Project

Originally, we were tasked to do data clean up and reporting for the school district. Upon the completion of our original anlaysis, we were told there were issues with one of the schools 9th grade test scores and were asked to nullify their test scores and re run the analysis.


Below, we will walk through the impact of adjusting the scores.

The original script is the file below:

[PyPoll_Challenge.py] (https://github.com/pritchardjeff/Election_Analysis/blob/master/PyPoll_Challenge.py)

The new script is the file below:

[PyPoll_Challenge.py] (https://github.com/pritchardjeff/Election_Analysis/blob/master/PyPoll_Challenge.py)

### Results

- How is the distrcit summary affected?
  - Average Math score went from 79.0 to 78.9
  - Average Reading score stayed the same due to rounding
  - % passing math went down from 75% to 74%
  - % passing reading went down from 86% to 85%
  - % Overall Passing went from 65% to 64%
  
- How is the school summary affected?
  - Only school impacted is Thomas High School
  - All fields remained the same other than the average reading score and average math score
  - The average reading score went down from 83.89488% to 83.896082%
  - The average math score went down from 83.41839% to 83.350937%

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
  - In terms of % overall passing, Thomas High school went from the 2nd highest performing school to the 5th highest performing school.
  
- How does replacing the ninth-grade scores affect math and reading scores by grade?
  - The only scores impacted were the 9th grade scores at Thomas High School, and the averages were replaced with "nan" values.
  
- How does replacing the ninth-grade scores affect scores by school spending?
  - The only spending range impacted is the $630-644 bucket
  - The % Passing Math went from 73% to 67%
  - The % Passing reading went from 84% to 77%
  - The % Overall passing went from 63% to 56%
  
- How does replacing the ninth-grade scores affect scores by school size?
  - The only school size impacted was the Medium (1000-2000) bucket
  - The % Passing Math went from 94% to 88%
  - The % Passing Reading went from 97% to 91%
  - The % Overall Passing went from 91% to 85%
  
- How does replacing the ninth-grade scores affect scores by school type?
  - The Charter schools were the only school type impacted
  - The % Passing Math went from 94% to 80%
  - The % Passing Reading went from 97% to 93%
  - The % Overall Passing went from 90% to 87%
  
The result output can be found in the following file:

[election_analysis.txt] (https://github.com/pritchardjeff/Election_Analysis/blob/master/Analysis/election_analysis.txt)

### Summary

Overall, the major impact from removing the 9th grade scores from Thomas High School are:
- Thomas High School performace relative to other schools in the district has been overstated
- The performance of schools in the $630-644 spend per student per year bucket was overstated
- The performance of schools in the Medium (1000-2000) size bucket was overstated
- The performance of charter schools was overstated



