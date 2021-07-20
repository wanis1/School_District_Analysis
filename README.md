# SCHOOL DISTRICT ANALYSIS

## OVERVIEW
The purpose of this project is to analyze student data coming from all the schools in PyCity. The data is based on standardized math and reading test results for all the students between grade 9th and 12th. The analysis is done to uncover any trends between the overall students performance, and student funding, type of school or population of school.
In this project, we also took into consideration the academic dishonesty reported for 9th graders of Thomas High School.

## RESULT
As a result of academic dishonesty, we eliminated the test scores for 9th graders of Thomas High School by replacing them with NaN's. Thus, changing the data has affected the results in following ways:

### District Summary
District summary result is not affected as much because Thomas High School(THS) only had a total number of 461 9th graders as compared to  a total of 39,170 students, whose data is collected. 

>![image](https://user-images.githubusercontent.com/86074187/126113714-f6dd29cc-dc9c-42e7-84ec-dd900b568665.png)

### School Summary
In school summary only the results for THS changed, because only the data for THS changed.

>![image](https://user-images.githubusercontent.com/86074187/126114147-3a16bca9-c2fe-4663-9f2c-847ffbfd4a64.png)

### Thomas High School’s Performance
Thomas High School has a total of 1,635 students out of which results for 461 students were removed from the data. However, by making this change THS's performance was not affected much. The reason for that is the data after excluding the 9th graders was analyzed only for 10th, 11th and 12th graders. 

>![image](https://user-images.githubusercontent.com/86074187/126116850-24ac10d5-a720-43c5-92f9-7a451bb85c28.png)

### Math and Reading Scores by Grade
Math and Reading Scores were unaffected. The only thing that changed is there "NaN" in the 9th grade section for math and reading score. An image of math score is attached for reference:

>![image](https://user-images.githubusercontent.com/86074187/126118280-1f3e6b87-ef0b-4c30-a68d-d0c9942299c1.png)

### Scores by Scool Spending, Size and Type
Math and reading scores by spending, size and type are unaffected. The scores are reflected in the images below:

#### Spending

>![image](https://user-images.githubusercontent.com/86074187/126244463-08e0515a-8523-4720-89db-169bb5db0604.png)

#### Size

>![image](https://user-images.githubusercontent.com/86074187/126244546-fd93e6a5-b1f4-4c9c-819c-ade93810bb76.png)

#### Type

>![image](https://user-images.githubusercontent.com/86074187/126244616-56b961c4-c131-497e-bbc3-3964dbd15443.png)

## SUMMARY
After eliminating the 9th graders from THS, following changes were reflected in the analysis:
- The average scores of Thomas High School for math decreased by 0.06
- The average scores of Thomas High School for math increased by 0.05
- The overall passing percentages of Thomas High School decreased slightly by 0.3%


