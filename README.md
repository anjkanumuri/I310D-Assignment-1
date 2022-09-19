# I310D-Assignment-1
SAT Score vs Graduation rate
1. Firstly, I collected data on SAT scores by composition in the New York City area, including their school name and average scores. This can be found in the repository under '2012_SAT_Results.csv.'
2. I then converted the attributes (Number of SAT Test Takers, SAT Critical Reading Avg Score, SAT Math Avg Score, SAT Writing Avg Score) from strings to integers after cleaning some inconsistencies in the data. 
3. I then plotted each of the integer attributes against the number of observations in the form of histograms. This helped me better understand the mean and averages in the data. I then added new columns after finding the sum of the compositions in order to easily compare each school. 'Sum of scores' is for this dataset and 'sum' will allow me to merge this dataset with my next dataset. This also allowed me to understand which schools had students who averages above 2000/2400, below 1000/2400, etc. 
4. I then plotted a scatter graph to show the correlation between the number of test takers and their scores. I realized that since the slope is close to 0 there is a very slight positive correlation between the number of people who took the test in each school and the average score. This can be seen in Graph 1 in the repository.
5. Lastly, I merged this with another dataset which consisted of graduation rates for school. Using the similar DBN value in both datasets, I merged the graduation rates with the SAT scores. As seen in the graph, I found that schools with the highest graduation rates had the highest SAT scores of above 2000. The other scores are quite uniform across schools with varied graduation rates. However, schools with the lowest graduation rates tended to have lower SAT scores.
6. This new dataset can be found in the repository under '2005-2010_Graduation_Outcomes.'
7. A potential bias in the data is the fact that the SAT Scores are for 2012. However, the graduation rates only show the rates until 2010. Although tt is unlikely that these rates changed significantly, it is important to note.
