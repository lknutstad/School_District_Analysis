# School District Analysis

# Overview
The School board has identified academic dishonesty in the reading and math grades for Thomas High School (THS) 9th graders.  They have requested these grades be removed from the database and all subsequent analysis be adjusted.

# Objective
The reading and math scores for THS 9th graders need to be replaced with NaNs while keeping the rest of the data intact. Then, the school district data needs reanalyzing.

# Results

## The District Summary 

Without removing THS 9th graders math and reading scores, the averages scores for math, reading, and overall passing were as follows:

![District Summary Original](Resources/district_summary_original.jpg)

After removing the compromised 9th grade results, an increase was observed in % passing math, % passing reading, and % overall passing:
![District Summary Modified](Resources/district_summary_modified.jpg)





## The School Summary
Without removing THS 9th graders math and reading scores, the averages scores for math, reading, and overall passing were as follows:

![School Summary Original](Resources/school_summary_original.jpg)

After removing the compromised 9th grade results, an increase was observed in % passing math, % passing reading, and % overall passing:

![School Summary Modified](Resources/school_summary_modified.jpg)


## Thomas High School Relative Performance
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?  A small, but insignicant change in school performance is observed with no effect on overall relative ranking.

Including the  THS 9th graders:
![Top Summary Original](Resources/top_schools_original.jpg)
 
Excluding the THS 9th graders:
![Top Summary Modified](Resources/top_schools_modified.jpg)



## Other Metrics

How does replacing the ninth-grade scores affect the following

Math and reading scores by grade

NaNs are listed in modified analysis:

![Math scores by Grade Original](Resources/math_scores_by_grade_original.jpg) ![Math scores by Grade Modified](Resources/math_scores_by_grade_modified.jpg)
    
###Scores by school spending

NaNs are listed in modified analysis:
![Reading scores by Grade Original](Resources/reading_scores_by_grade_original.jpg) ![Reading scores by Grade Modified](Resources/reading_scores_by_grade_modified.jpg)
    
###Scores by school size

No difference is observed in scores by school size after removing THS 9th grade data

Including THS 9th grade data:
![scores per school size Original](Resources/scores_per_school_size_original.jpg)

Excluding THS 9th grade data:

![scores per school size Original](Resources/scores_per_school_size_original.jpg)

    
###Scores by school type 

No difference is observed in scores by school git type after removing the THS 9th grade data

Including THS 9th grade data:
![scores per school spending Original](Resources/scores_per_school_spending_original.jpg) 

Excluding THS 9th grade data:
    
![scores per school spending Modified](Resources/scores_per_school_spending_modified.jpg)



# Summary
Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:

- % passing math, % passing reading, & % passing overall by district increased
- % passing math, % passing reading, & % passing overall for THS decreased by => 0.5%.
- THS relative performance ranking by school did not change despite decrease in % passing math, % passing reading, & % passing overall
- No significant changes in scores by school type or size. 