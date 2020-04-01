# Machine Learning Capstone Project
# College Scorecard
## Features predicting a high retention and graduation rate
<br> </br>
## Motivation
The US Department of Education collects a vast number of data from postsecondary education institutions already for more than 2 decades. These data shall help students to fnd an appropriate college for their studies. Students and their families shall be able to compare costs and outcomes to make an informed choice about their higher education. For colleges it might be important to know how they can optimize retention and graduation as these metrics are important for them to maximize revenues and to be able to provide the best cost/beneft ratio to their students.
As I am European I am interested in having insight into the US college system. I am also interested in the outcome in comparison to European standards that are familiar to me.
<br> </br>
<br> </br>
## Results
For this capstone project in the field of education I had to go through the whole data science process from understanding the problem, gather data, understand the data, prepare the data, build models and evaluate them. As my question was not to build a model but to gain insight into data model deployment was not an issue.
As with most projects I spent  most of the time with understanding the data and preparing the data. Building models and getting results was the lesser part of my work.
The question I solved was: What are the most important college level features predicting a high retention and gratuation rate.
For this project I only used data for full time students in 4 year institutions.
I developed  dependent binary variables for retention and graduation and a selection of numeric features which I used as input for a RandomForest classifiaction model. As a benchmark I used a model only predicting the major class of the dependent variable. I evaluated the model against the benchmark and tested the robustness of the model predictions. As my model was significantly better than the benchmark model I used it to extract the most important features.
The 5 most important features predicting strong retention are the average faculty salary (AVGFACSAL), instructional expenditure per fulltime student (INEXPFTE), share of undergraduate afroamerican students (UGDS_BLACK), the average cost of attendance (COSTT4_A) and the share of part time undergraduate students (PPTUG_EF).
The 5 most important features predicting a strong graduation rate are the share of part time undergraduate students (PPTUG_EF), the average cost of attendance (COSTT4_A), instructional expenditure per full time student (INEXPFTE), percentage of degrees in liberal art and sciences, general studies and humanities (PCIP24) and the average faculty salary (AVGFACSAL).
4 out of 5 features overlap but they have different importances which I think can be attributed to different time frames.
The procedural (e.g. academic integration, student support services) and structural (e.g. composition of student population, institutional expenditures) aspects play a major role and make perfectly sense.
It is remarkable however that the correlation between retention and graduation is only a moderate 0.68. So some of the institutions seem to be good in retention but not in graduation rates or vice versa. This aspect however was not pursued further in this project.
<br> </br>
<br> </br>
## Libraries used
- Jupyter Notebook
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- Xgboost
<br> </br>
<br> </br>
## Files 
- .png files are the saved plots from EDA
- CollegeScorecard3.ipynb is the jupyter notebook
- .xlsx is the Excel file containing feature descriptions and more
- .csv files are dataframes of various cleaning and processing stages derived from original data frame
- original data frame is missing due to size constraints
<br> </br>
<br> </br>




