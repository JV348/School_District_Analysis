# School District Analysis
We have been analyzing data regarding standardized scores and funding for a school system so that the district may determine how to distribute future funds. As such, we have compared school types against their funding and test scores - resulting in the creation of various tables depicting the relevant information.

## Overview 
It was brought to our attention that some degree of academic dishonesty occurred in the 9th grade class at Thomas High School. As a result, it was determined that this data should be removed from the final analysis. We have since taken the steps necessary to properly analyze the data without those particular ninth graders.

## Results

- How is the district summary affected?

After comparing the original district summary with the modified challenge district summary, we can see that the data output is not very different between the two. This trend persists throughout the new analysis. However, there are slight differences in output numbers. As seen in the analysis, the modified data shows a small variation in average scores and percentages. These variations range from 0.01% to 0.03% in difference as compared to the original output. In short, the new district summary is showing a decrease in numbers that reflects the removal of a small amount of ninth graders. 
  
   ![Original_District_Summary_DF](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Original_District_Summary.png)
    
   ![Challenge_District_Summary_DF](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Challenge_District_Summary.png)


- How is the school summary affected?

We created a dataframe that showed the statistics for all schools with the original data and, subsequently, with the modified data. In this case, the modified data is only relevant to Thomas High School; therefore, that row is the only difference between the two versions. We can clearly see that removing the ninth grade from Thomas High School has slightly decreased their overall percentages and math averages. This is so because the number of students removed from the analysis were noteworthy but very significant. Essentially, the new dataframe is not a true reflection of passing rates for Thomas High School, but it is not very different from the original. 

   ![Original_School_Summary_DF](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Original_School_Summary.png)
    
   ![Challenge_School_Summary_DF](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Challenge_School_Summary.png)


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Despite the slight differences in averages and percentages for Thomas High School in the new dataframes, it seems that the changes were not enough to remove the high school from the Top 5 Schools. In fact, it still remains ahead of Griffin High School. 

   ![Original_Performance](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Original_Performance.png)
    
   ![Challenge_Performance](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Challenge_Performance.png)
 
 
- How does replacing the ninth-grade scores affect the following:

    a)Math and Reading Scores by Grade
    
    The only data that was affected in this section was that of the 9th grade for Thomas High School. In the new dataframes, we can see that the 9th grade average math and reading scores have been replaced by "NaN".
    
   ![Original_Scores_by_Grade](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Original_Scores_by_Grade.png)
 
   ![Challenge_Scores_by_Grade](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Challenge_Scores_by_Grade.png)


    b)Scores by School Spending
    
    Thomas High School fell into the bin for $630 - $644 and therefore only affected the data for that row in the dataframe. In the modified dataframe, we can see that all averages and percentages decreased by a slight amount except for average reading scores - which marked a very small increase. Still, the general trend is a decrease in passing rates as a result of the 9th grade removal. 
    
   ![Original_Scores_by_Spending](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Original_Scores_by_Spending.png)
    
   ![Challenge_Scores_by_Spending](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Challenge_Scores_by_Spending.png)
 
 
    c)Scores by School Size
    
    Thomas High School was considered a medium sized school with 1635 students. With the removal of 461 9th grade students from Thomas High School analysis, we found similar trends as before. All percentages and averages have decreased slightly except for average reading scores in the medium school size row. 
   ![Original_Scores_by_Size](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Original_Scores_by_Size.png)
    
   ![Challenge_Scores_by_Size](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Challenge_Scores_by_Size.png)
   
   
    d)Scores by School Type
    
    Thomas High School was designated as a Charter school, therefore any alterations to Thomas High School data affected the overall analysis for charter schools in this section. The new dataframe also conformed to the previously established trend; we saw small decreases in all percentages and average math scores but a small increase in average reading scores. 
    
   ![Original_Scores_by_Type](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Original_Scores_by_Type.png)
    
   ![Challenge_Scores_by_Type](https://github.com/JV348/School_District_Analysis/blob/e68f2d4730e2191d316e7216a169c550d980977e/Resources/Challenge_Scores_by_Type.png)
  
# Summary
After completing the analysis with the modified data, we can conclude that the removal of the 9th grade class of Thomas High School had a miniscule effect upon the overall analysis of the district. That makes sense because 461 students out of a total 39,170 students in the district was a considerably small amount. Nonetheless, we were able to establish a trend across the new analysis. 

Overall, passing rates decreased, as seen by a decrease in average math scores and all passing percentages across the board. The changes were not astounding but still noteworthy. However, it was seen that average reading scores slightly increased in every section of the analysis. 9th grade reading scores at Thomas High School may have been below average, and the removal of that data led to a small increase in average reading scores. Either way, Thomas High School still maintained positive statistical performance, although its reputation for academic dishonesty remains a different story. 
