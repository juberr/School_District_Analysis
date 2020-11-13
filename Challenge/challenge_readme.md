#  Overview of School District Analysis

## Introduction

Working with Maria, we created six Pandas Dataframes with the data from the school and student CSV files. After our initial analysis, it was brought to our attention that there was evidence of academic dishonesty amongst 9th graders from Thomas High School. To ensure an honest analysis, it was imperative that we replace the 9th grade Thomas high school data with NaN (Not A Number) values. The following report presents the effects of this change in the data.

## Results

* How is the district summary affected? 
    * For the district summary, the average reading score stayed at 81.9, but all other metrics took a reduction after replacing all ninth grade data with NaNs.

    ![district summary before](https://github.com/juberr/School_District_Analysis/blob/main/Challenge/screenshots/district%20summary%20before.png?raw=true)

    ![district summary after](https://github.com/juberr/School_District_Analysis/blob/main/Challenge/screenshots/district%20summary%20after.png?raw=true)

* How was the school summary affected? 
    * Across each metric (except average reading score), Thomas High School is reporting lower grades and passing percentages after replacing all ninth grade data with NaNs.

    ![school summary before](https://github.com/juberr/School_District_Analysis/blob/main/Challenge/screenshots/school%20summary%20before.png?raw=true)
    
    ![school summary after](https://github.com/juberr/School_District_Analysis/blob/main/Challenge/screenshots/school%20summary%20after.png?raw=true)

* How does replacing the ninth grader's math and reading scores affect Thomas High School’s performance relative to the other schools?
    * After replacing the ninth grader's math and reading scores with NaN values, Thomas High School's performance reamains at second place overall in the district. Though the gap between Thomas High School and Griffin High School Has become significantly closer (90.63 to 90.60)

    ![top schools before](https://github.com/juberr/School_District_Analysis/blob/main/Challenge/screenshots/top%20schools%20before.png?raw=true)

    ![top schools after](https://github.com/juberr/School_District_Analysis/blob/main/Challenge/screenshots/top%20schools%20after.png?raw=true)

* How did replacing ninth grade scores affect:

    * Math and reading scores by grade?
        * There is now no data for ninth graders from Thomas High School in both dataframes.

    * Scores by school funding?
        * No observable difference in scores by school funding once formatted.
    
    * Scores by school size
        * No observable difference in scoress by school size  once formatted.
    
    * Scores by school type
        * No observable difference in scores by school type once formatted.

# Summary

Removing all of the ninth grade scores from Thomas High School caused the following effects:

* Lowered the overall district summary dataframe for the average math score, overall passing math and reading percentage, and over all passing percentage

* Lowered all metrics for the school summary dataframe

* Brought the race for second place in overall school rankings much closer between Thomas High School and Griffin High School

* Makes no data available for the my grade analysis for Thomas High School ninth graders

To get a more accurate picture, the extent of the academic dishonesty within Thomas High School ninth graders should be investigated. Removing all ninth grade THS students also removes those students with lowers scores thuse skewing the effects of the acadenic dishonesty.





    