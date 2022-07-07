# School_District_Analysis
Use Python and Pandas library to analyze school district data
## Overview
In this projects, we are going to analyze the test data for each students at each school, to showcase the school performance trends and patterns, and finally write up a report to describe how the school budgets, size and type influence the school performance, this report will be a reference to the school board to make decisions for schools distribution.<br/>
However, there shows academic dishonesty in Thomas High School ninth graders, so we need replace their math and reading scores with NaN, and repeat the school district analysis to describe how these changes affected the overall analysis.
## Resources
Data source: schools_complete.csv,  students_complete.csv<br/>
Software: Python 3.7.6   Jupyter Notebook 6.4.8
## Results Analysis
1. Replace the 9th grade reading and math scores at Thomas High School with NaN:<br/>
![replace scores for Thomas 9th graders](https://user-images.githubusercontent.com/107179765/177722135-9e7e2655-2387-4ffb-a32f-389400cff706.png)
2. Repeat the school district analysis according to the following metrics:<br/>
  -	District summary
  -	School summary
  -	Top 5 and bottom 5 performing schools on overall passing rate
  -	Average math and reading scores for each grade level from each school
  -	Scores by school spending per student, by school size, and by school type
### District summary
District summary before changes:<br/>
![before 1 district summary](https://user-images.githubusercontent.com/107179765/177725998-8944d2f1-0f72-4360-b5de-c07203b1a3ef.png)<br/>
District summary after changes:<br/>
![after 1 district summary](https://user-images.githubusercontent.com/107179765/177726030-657cb368-e310-4e66-b81f-7316ebdf1bc1.png)<br/>
From the pictures ,we can see that
### School summary
Per school summary before changes:<br/>
![before 2 school summary](https://user-images.githubusercontent.com/107179765/177726715-d7600623-41e4-4775-b055-2a4a70881b2c.png)<br/>
Per school summary after changes:<br/>
![after 2 school summary](https://user-images.githubusercontent.com/107179765/177726784-358aac2e-ad57-47d7-8009-7b5bd54a145a.png)<br/>
As we can see
### Top 5 and bottom 5 performing schools on ovrall passing rate
Top 5 performing schools before changes:<br/>
![before 3 top5 schools](https://user-images.githubusercontent.com/107179765/177728297-49def659-9bf0-456f-8197-6ec59d135c3a.png)<br/>
Top 5 performing schools after changes:<br/>
![after 3 top5 schools](https://user-images.githubusercontent.com/107179765/177728348-3f3d2080-9b8c-4f71-bac4-6128a48594ba.png)<br/>
Bottom 5 performing schools before changes:<br/>
![before 4 bottom5 schools](https://user-images.githubusercontent.com/107179765/177728393-330bbca7-d293-4b69-88b2-e7abfb297084.png)<br/>
Bottom 5 performing schools after changes:<br/>
![after 4 bottom5 schools](https://user-images.githubusercontent.com/107179765/177728438-34bd4e08-dee2-4cb6-9335-510313213fd5.png)<br/>
Before and after replacing the ninth-grader’s math and reading scores, Thomas High School remains in second place in the top performing schools. While before, Thomas High School was closer to Cabrera High School, now Thomas High School is closer to Griffin High School in performance.
### Average math and reading scores for each grade level from each school
Average math and reading scores before changes:<br/>
![before 5 average math score](https://user-images.githubusercontent.com/107179765/177729074-0b2e39ff-526f-4b6c-9051-7ffeb5d9fb5e.png)
![before 6 average reading score](https://user-images.githubusercontent.com/107179765/177729125-26d828f2-9151-4631-b4f2-d7c62c41e600.png)<br/>
Average math and reading scores after changes:<br/>
![after 5 average math score](https://user-images.githubusercontent.com/107179765/177729225-e791c4cc-fef1-403e-b5c3-8725565215a4.png)
![after 6 average reading score](https://user-images.githubusercontent.com/107179765/177729240-38c65c01-fd6c-4f56-a17c-f7ca63a29c59.png)<br/>
As we can see,
### Scores by school spending per student, by school size, and by school type
1. Scores by school spending per student before changes:<br/>
![before 7 school spending](https://user-images.githubusercontent.com/107179765/177730182-0ad24413-b675-421c-87dd-f95fc2cdc50e.png)<br/>
   Scores by school spending per student after changes:<br/>
![after 7 school spending](https://user-images.githubusercontent.com/107179765/177730210-6584fc85-e27e-4b49-b290-2502445fde84.png)<br/>

2. Scores by school size before changes:<br/>
![before 8 school size](https://user-images.githubusercontent.com/107179765/177730250-7437667d-14b4-4840-b7ec-d033dd15ee29.png)<br/>
   Scores by school size after changes:<br/>
![after 8 school size](https://user-images.githubusercontent.com/107179765/177730270-b132a6c0-0c14-434c-bc4a-f3924b4bf06c.png)<br/>

3. Scores by school type before changes:<br/>
![before 9 school type](https://user-images.githubusercontent.com/107179765/177730291-82df27e5-6489-49c8-93f4-98b43da8eff3.png)<br/>
   Scores by school type after changes:<br/>
![after 9 school type](https://user-images.githubusercontent.com/107179765/177730330-e340727d-4993-48df-a78d-20de678cca93.png)<br/>
## Summary
There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced 

