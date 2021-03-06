# School_District_Analysis
Insights for student funding and standardized test scores for budgets
## Overview of Project
### Purpose of this analysis

The purpose of this analysis is to write a report describing changes that affect an overall analysis of the school district after evidence showed academic dishonesty for a specific grade. The goal was to keep the majority of the original data intact while replacing dishonest test scores with NaN.
Example:

![student data](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/student_data_nan.png?raw=true)

## Results


### How is the district summary affected

![district before](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/district_summary_before.png?raw=true)

![district after](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/district_summary_after.png?raw=true)

The images show that the average math score changed slightly as is was .1 less than before. The reading score did not seem to be affected as it stayed the same at 81.9. The percent passing math, reading and overall passing percentage were all lowered slightly after Thomas High School ninth graders' scores were replaced with NaN. 

### How is the school summary affected

![school summary](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/school_summary.png?raw=true)

![school summary after](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/school%20summary%20after.png?raw=true)

The school summary for Thomas High School seemed to have a major change after the ninth grade scores were replaced with NaN. The percentages for math, reading and overall were changed when I omitted the ninth graders in the overall percentages. Percents showed to have increased when the suspected scores were not calculated.

### How does replacing ninth graders math and reading scores affect Thomas HS performance relative to the other schools

Relative to the other schools summary, Thomas High School was moved up with the other schools when considering the percent overall passing after replacing the scores. After removing the ninth graders, the percentages seem to improve.

### How does replacing ninth graders scores affect the following:
 - math and reading scores by grade
    
    ![math scores](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/math_scores_by_grade.png?raw=true)

    ![reading scores](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/reading_scores_by_grade.png?raw=true)

    Thomas HS has the obvious NaN for ninth grade when comparing with the other schools for math and reading scores.

 - scores by school spending

    ![spending before](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/scores%20by%20spending%20and%20size%20BEFORE.png?raw=true)
    
    ![spending after](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/scores%20by%20spending%20and%20size%20AFTER.png?raw=true)

    The before and after show only slight differences in the percentages for Thomas HS for math, reading and overall passing. The spending rages still stay the same.

 - scores by school size

    ![scores by size](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/scores%20by%20size.png?raw=true)

    The scores by size proved to have no changes and was calculated to be exactly the same even with Thomas High School ninth graders omitted from the count. 

 - scores by school type

    ![scores by type](https://github.com/myljacobo/School_District_Analysis/blob/master/Resources/scores%20by%20school%20type.png?raw=true)

    The scores by type also proved to have no changes and was calculated to be exactly the same even with Thomas High School ninth graders omitted from the count. 

## Summary

After reading and math scores for Thomas High School have been replaced with NaN after concerns of tampering, there have been definite but slight changes to the school district analysis. The student data has the most obvious change when reviewing each ninth grader individually, you can see NaN in place of previous scores and every other student will have numbered grades. Also when reviewing the scores by grade, Thomas HS has NaN in place of a numerical value for ninth grade. The district summary also had a change, even if slightly, as all the schools in whole had their percentage calculated for passing math and reading and the percentages proved to have a change. Thomas High School did have a major change in the their individually calculated percentages for passing math and reading when omitting the ninth graders. 
