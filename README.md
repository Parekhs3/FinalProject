# FinalProject

Title: "Education in Europe: A Data Analysis"
Group: Sweta Parekh, Alison Iniguez, and Ryan Stanisci
Format: html

# Introduction 
In this analysis, we explore diffrent factors in realtion to education varied across European countries. 
Our main objective is to understand the government education spending correlates with student outcomes and -
weather significant exsit amongs reginoal groups. 

# Data Source 
The data was downloaded from [data.europa.ed](https://data.europa.eu/en).
The dataset includes information about education expenditure (% of GDP), student-teacher-ratio, -
average test scores, and region (such as., Northern Europe, Southern Europe, etc.). 

# Variables 
- 'Country': Name of the country 
- 'Region': Region of Europe
- 'Education_Spending': Government expenditure on education (% of GDP)
- 'Student_Teacher_Ratio': Number of students per teacher
- 'Test_Score': Average standarized student test score

# Questions 
1. Is there a significant difference in education spending between Northern and Southern European countires?
2. Does higher education spending correlate with better student test scores?

# Descriptive Statistics 



# Histrogram of the education Spending 
'''''{r}
hist(data$Education_Spending 
  main = "Histrogram of Education Spending",
  xlab = "Education Spending (% of GDP)", 
  col = "skyblue", 
  border = "white")
  
