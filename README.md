# School_District_Analysis
Use Python and Pandas library to analyze school district data
## Overview
In this projects, we are going to analyze the test data for each students at each school, to showcase the school performance trends and patterns, and finally write up a report to describe how the school budgets, size and type influence the school performance, this report will be a reference to the school board to make decisions for schools distribution.<br/>
However, there shows academic dishonesty in Thomas High School ninth graders, so we need replace their math and reading scores with NaN, and repeat the school district analysis to describe how these changes affected the overall analysis.
## Resources
Data source: schools_complete.csv,  students_complete.csv<br/>
Software: Python 3.7.6   Jupyter Notebook 6.4.8
## School District Analysis
### Process of Analysis
1. Replace the 9th grade reading and math scores at Thomas High School with NaN:<br/>
![replace scores for Thomas 9th graders](https://user-images.githubusercontent.com/107179765/177722135-9e7e2655-2387-4ffb-a32f-389400cff706.png)
2. Repeat the school district analysis according to the following metrics:<br/>
  -	District summary
  -	School summary
  -	Top 5 and bottom 5 performing schools on overall passing rate
  -	Average math and reading scores for each grade level from each school
  -	Scores by school spending per student, by school size, and by school type<br/>
### Results of Analysis
In this challenge, the school district analysis are based on two scripts I wrote:<br/>
1.PyCitySchools_practice_testing.ipynb: is the script before 9th grade scores being replaced.<br/>
2.PyCitySchools_Challenge.ipynb:        is the script after 9th grade scores being replaced.<br/>
I'll analysize the data based on the output of those two scripts. Let's describe the analysis results of merics below:
#### District summary
In order to better comparing the slight changes between the two pictures, I choose the unformatted dataframes to show the difference:<br/>
District summary before changes:<br/>
![1 district summary before](https://user-images.githubusercontent.com/107179765/177860541-ed4d3d4d-5070-4b48-a648-a2390d40ce7a.png)<br/>
District summary after changes:<br/>
![1 district summary after](https://user-images.githubusercontent.com/107179765/177860527-602b72e4-7dde-4f5e-a33e-56a09edfe8f7.png)<br/>
From the pictures above we can see that the overall data haven't changed too much by the academic dishonesty. The average scores and the percentage of passing scores dropped slightly, it may because of the 9th grade of Thomas High School having a good cheating scores, with a lot of students having math and reading scores greater than 70.
#### School summary
In order to better observing the changes on Thomas High School, I use the code "per_school_summary_df.tail()" to show the place where Thomas High School is in:<br/>
Per school summary before changes:<br/>
![before 2 school summary](https://user-images.githubusercontent.com/107179765/177852830-0ab93948-9fb5-4cb0-9578-3b5d78067ce9.png)<br/>
Per school summary after changes:<br/>
![after 2 school summary](https://user-images.githubusercontent.com/107179765/177852889-c7fb8141-efe1-4c1e-92e8-b37a3a4a9d6d.png)<br/>
As we can see, the overall data are nearly the same. Except for the decrease on other scores data, only the average reading scores has an slight increase by 0.05. 
While there is an increase in the average reading score, there is a decrease in the percentage of passing reading. This may told us that the average reading scores of 9th grade is a little lower than the average reading scores of 10th-12th grade, which means most of the 9th grade students got about 70 or so scores on their reading scores.
#### Top 5 and bottom 5 performing schools on ovrall passing rate
1. Top 5 performing schools before changes:<br/>
![before 3 top5 schools](https://user-images.githubusercontent.com/107179765/177856133-8c98bf08-1fd3-4d2d-a0e7-c1a4b337ddaa.png)<br/>
   Top 5 performing schools after changes:<br/>
![after 3 top5 schools](https://user-images.githubusercontent.com/107179765/177856158-33fe027c-d2dc-4ca2-9483-4336a280ebc4.png)<br/>
2. Bottom 5 performing schools before changes:<br/>
![before 4 bottom5 schools](https://user-images.githubusercontent.com/107179765/177728393-330bbca7-d293-4b69-88b2-e7abfb297084.png)<br/>
   Bottom 5 performing schools after changes:<br/>
![after 4 bottom5 schools](https://user-images.githubusercontent.com/107179765/177728438-34bd4e08-dee2-4cb6-9335-510313213fd5.png)<br/>
From the pictures above, we can see that, the orders of top 5 and bottom 5 performing schools reamin the same as before. In the top 5 performing schools, the overall passing scores of Thomas High School has dropped a little bit, but this didn't influence the Thomas High School to be the No.2 of top 5 performaing schools. 
#### Average math and reading scores for each grade level from each school
Average math and reading scores before changes:<br/>
![before 5 average math score](https://user-images.githubusercontent.com/107179765/177854445-53e86ed8-580f-4d14-b7b8-969054253b88.png)
![before 6 average reading score](https://user-images.githubusercontent.com/107179765/177854103-697717f0-c5ad-4789-adab-d61bdcea718c.png)<br/>
Average math and reading scores after changes:<br/>
![after 5 average math score](https://user-images.githubusercontent.com/107179765/177855430-19641414-ca15-4efa-968c-cf32c9b6c6c0.png)
![after 6 average reading score](https://user-images.githubusercontent.com/107179765/177855475-568b0131-f0bf-4c17-a239-088bbcddade8.png)<br/>
As we can see, the only change of these charts are the average math and reading scores by ninth grade of Thomas High School were relpaced with NaN, which create a null value for that column in the 9th grade scores.
#### Scores by school spending per student, by school size, and by school type
Since the scores by school spending per student shows no changes after rounding(same as school size and school type). So again, I'll use the unformatted data to show the analysis results:
1. According to per_school_summary dataframe,the per student budget of Thomas High School is $638, which belongs to the spending range:$630-644.<br/>
   Scores by school spending per student before changes:<br/>
![7 school spending before](https://user-images.githubusercontent.com/107179765/177900012-3ae5e76c-d8ae-4cf6-bbd5-39d6aaa8be9b.png)<br/>
   Scores by school spending per student after changes:<br/>
![7 school spending after](https://user-images.githubusercontent.com/107179765/177900021-51035c8d-32f2-4bcf-9b0e-6c8ac02e1c5a.png)<br/>
2. The total students of Thomas High School is 1,635, which belongs to the size:Medium.<br/>
   Scores by school size before changes:<br/>
![8 school size before](https://user-images.githubusercontent.com/107179765/177900026-c128a1aa-6fdb-4412-a4b2-1708abd1a3d4.png)<br/>
   Scores by school size after changes:<br/>
![8 school size after](https://user-images.githubusercontent.com/107179765/177900035-e791b328-5258-4ac7-8148-506e8b095b4f.png)<br/>
3. The type of Thomas High School belongs to the type:Charter.<br/>
   Scores by school type before changes:<br/>
![9 school type before](https://user-images.githubusercontent.com/107179765/177900043-77708753-f0c5-4439-a121-cc594f083c6d.png)<br/>
   Scores by school type after changes:<br/>
![9 school type after](https://user-images.githubusercontent.com/107179765/177900058-e29fc9d3-590b-4fe6-aa99-56c128a5de56.png)<br/>
Through the data we can see that, it is almost negligent when the 9th grade scores are changed with NaN when it comes to scores by spending per student, by school size, and by school type.
## Summary
The student number of 9th grade Thomas High School is 461, the student number of Thomas High School is 1,635, while the total student number of all schools is 39,170. Compare to the total student number, the number of student whose scores need to be replaced is only a small portion of the total number, which means only 1.17% of total students had their scores being replaced.<br/> 
Overall, as the results shows, there wasn't too much great changes after replacing the 9th grade reading and math scores at Thomas High School with NaN. Let's talk about these changes briefly. 
1. In the district summary of all the schools, the average math and reading scores as well as the percentage passing dropped slightly. This shows that the ninth grade of Thomas High School had an overall positive impact on the total school results.
2. When it comes to Thomas High School, the average math scores as well as the percentage passing also dropped slightly, except for the average reading scores. But Thomas High School remains the No.2 placement of the top 5 performing schools. Interestingly, all of the top 5 performing schools are charter, while all of the bottom 5 performing schools are district.
3. After the scores of 9th grade being replaced, other grades of Thomas High School can still be analyzed with the average scores and percentage passing separately.
4. The impact on school spending, school size and school type analysis is negligent after changing the ninth grade scores. But from the chart we can see something interesting: a). the more each school spending on per student, the lower overall passing percentage they got. b). medium size of schools have the highest overall passing percentage. c). charter schools better performing than district schools, which we can also conclude from the top 5 and bottom 5 performing schools.

