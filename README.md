# I310D-Assignment-1
SAT Score vs Graduation rate

SAT scores are an important aspect of the college application process. The scores help colleges compare students from different high schools in order to understand students strengths, weaknesses, and readiness for college. Therefore, I believe that higher SAT Scores would have a strong positive correlation with a schools graduation rate. This data collection, processing, and analysis will help me find out if this is true.
1. Firstly, I collected data on SAT scores by composition in the New York City area, including their school name and average scores. This can be found in the repository under '2012_SAT_Results.csv.'
2. I then converted the attributes (Number of SAT Test Takers, SAT Critical Reading Avg Score, SAT Math Avg Score, SAT Writing Avg Score) from strings to integers after cleaning some inconsistencies in the data. 
3. I then plotted each of the integer attributes against the number of observations in the form of histograms. This helped me better understand the mean and averages in the data. I then added new columns after finding the sum of the compositions in order to easily compare each school. 'Sum of scores' is for this dataset and 'sum' will allow me to merge this dataset with my next dataset. This also allowed me to understand which schools had students who averages above 2000/2400, below 1000/2400, etc. 
4. I then plotted a scatter graph to show the correlation between the number of test takers and their scores. I realized that since the slope is close to 0 there is a very slight positive correlation between the number of people who took the test in each school and the average score. This can be seen in Graph 1 in the repository.
5. Lastly, I merged this with another dataset which consisted of graduation rates for school. Using the similar DBN value in both datasets, I merged the graduation rates with the SAT scores. As seen in the graph, I found that schools with the highest graduation rates had the highest SAT scores of above 2000. The other scores are quite uniform across schools with varied graduation rates. However, schools with the lowest graduation rates tended to have lower SAT scores.
6. This new dataset can be found in the README under the '2005-2010_Graduation_Outcomes' link below. The merged processed data is also below.
7. A potential bias in the data is the fact that the SAT Scores are for 2012. However, the graduation rates only show the rates until 2010. Although it is unlikely that these rates changed significantly, it is important to note. This can be seen in the repository under graph 2.

Files were too large so they were saved in google sheets - 
2005-2010_Graduation_Outcomes_-_School_Level.csv - https://docs.google.com/spreadsheets/d/1iwsQNJJJxqS9KYS2TVlFUyVwDOrfWb6r09skDyLIXGM/edit?usp=sharing
SATscoreGradrate - https://docs.google.com/spreadsheets/d/122bxKgl6ILLspKaheoECQHFwh6_uRFYtnxgXLMXC64k/edit?usp=sharing

A data type and description for each attribute in the processed data and original csv
<img width="1114" alt="Screenshot 2022-09-19 at 3 20 34 PM" src="https://user-images.githubusercontent.com/113871413/191109518-258084ec-2e02-4d1f-bf53-21e8627913a0.png">

API Endpoints for 2012 SAT CSV and 2005-2010 Graduation outcomes
https://data.cityofnewyork.us/resource/f9bf-2cp4.json
https://data.cityofnewyork.us/resource/vh2h-md7a.json

The MIT License (MIT)

Copyright (c) 2022 Anjali Kanumuri

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


