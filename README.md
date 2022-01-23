# School_District_Analysis
Use Python and Pandas to analyze school distrct data, as well as the trends in school performance based on key point value. In addition, use Jupyter Notebook to visualize the data. This analysis to help the board of DOE to make decision of the school budgets and funding. 

## Result
- How is the district summary affected?
  The total budget in this district is $24,649,428.00 for 39,170 students. When we look at the overall score passing rate just above the average. Therefore, the data only states the general date for the district. Table shown below. 
  
  > <img width="1111" alt="District Summary" src="https://user-images.githubusercontent.com/94089680/150662141-4dd47163-5efd-44c5-aa31-645603fcd5f1.png">

- How is the school summary affected?
  There are two types of school, which are district and charter. As we can see the picture shown below. The charter school has relatively smaller amount of student. Therefore, the charter schools overall passing rate are raletively higher than the district schools. 
  
  > <img width="863" alt="School Summary" src="https://user-images.githubusercontent.com/94089680/150662352-0e5bfdf8-8b29-42d3-9fa6-d58a49c4dc05.png">

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  Since there are some missing scores in the dataset for ninth grade in Thomas High School. Thus, the percentage passing rate of math, reading, and overall scores are lower than other charter schools. The lack of information may cause the percentage passing rate inaccurate. The total students number did not match the students who actually received grades. 
- How does replacing the ninth-grade scores affect the following, table provided below:
  1. Math and reading scores by grade improves significantly based on the accurate information provided. 
  2. Scores by school spending didn't change because we only drop the scores which had missing information.  
  3. Scores by school size didn't change because we only drop the scores which had missing information.
  4. Scores by school type didn't change because we only drop the scores which had missing information.

> <img width="876" alt="School Summary after remove 9th graders" src="https://user-images.githubusercontent.com/94089680/150662829-624b7638-fd2b-4e37-8e4b-dbe34a74bc12.png">

> <img width="807" alt="School Summary with budget and size" src="https://user-images.githubusercontent.com/94089680/150662994-6251e411-f727-44f2-9442-63df0b30aee3.png">

## Summary
After I dropped all ninth graders in Thomas High School, the percentage of passing rate improve significantly. Due to some students have missing scores for math and reading for ninth grades, the passing percentage dropped nearly 28% which affects the final school summary report. That may cause the board of DOE cutting the budget in future planning due to the inaccurate percentage rates.   
