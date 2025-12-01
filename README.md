# Personal-Dataset-Project-
## Introduction 
For my personal dataset project, I decided to explore if there was a link between the size of the sample of ED (Emergency Department) visits due to asthma and a metric that was derived by combining the percentage of visits with their standard error across different states in the United States.
## Data Processing 
The basis for the data cleaning process was pretty solid because the numbers, which were obtained from a credible organization such as the CDC. On the other hand, the presentation of the data was the biggest problem: it was not very readable and could not be directly used in a program like Excel, which meant that a lot of manual work had to be done to change the variables and make sure they were structurally compatible.
## Exploratory Analysis
Investigating data through the scatterplot, revealing the weak negative correlation between sample size and the combined asthma visit percentage plus standard error, was the first step.

Scatterplots: 

![Logistic graph 1](https://github.com/user-attachments/files/23866890/Untitled.document.pdf)

![Logistic graph 2](https://github.com/user-attachments/files/23866893/Untitled.document.1.pdf)

## Logistic Repression
For this component, I selected to use logistic regression, a supervised learning method that we studied in class, as it directly matched my research inquiry regarding the relationship between the sample size and the rate of asthma-related Emergency Department (ED) visits. According to the plot, there is just a slight negative correlation between the size of the samples and the combination of the standard error plus the percentage of patients visiting the ED due to asthma. The data points across the graph are extremely scattered. The weak linear pattern that was observed and implied that just making simple descriptive comparisons was not good enough to clarify the fluctuations in asthma ED visits. The scatterplot revealed that there was high variability, no distinct clustering, and no trending, thus logistic regression was the next logical step to check if certain situations like higher or lower combined percentages of asthma visits could be forecasted based on sample size as a binary outcome. From this analysis, I inferred that sample size by itself is not a reliable predictor of the difference in rates of asthma ED visits, thus confirming what was visually portrayed by the scatterplot: the territorial diversity is caused by factors other than the number of visits being recorded.
