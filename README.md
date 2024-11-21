# Project 2: The relationship between eating habits and productivity.


## Executive Summary
This report examines the relationship between eating habits and productivity of university students. Specifically, it analyses:

- How the amount of caffeine intake affects individual productivity.

- How the number of meals affects individual productivity. 

As the amount of caffeine intake and the number of meals increase, the individual’s productivity also increases.


## Initial Data Analysis (IDA)
### Source
The data used was collected from a Google Form survey sent out to university students on Ed Discussions and through messages sent out by project members.  
(https://forms.gle/bQDbGSTCYh7XsLQ59)


### Structure
The survey received 50 responses, each row of the dataset represents an individual participant. The dataset has 8 columns of variables:

- 4 qualitative: gender, productivity timing, consume caffeine or not, past performance.

- 4 quantitative: age, meal frequency, productivity rate, caffeine intake.
  

### Limitations
- Volunteer bias: The survey was introduced as “investigating how eating habits affect productivity”, therefore, those who responded might be more interested in this topic than those who don’t, leading to a non-representative sample.  

- Measurement bias: The question “How many times a day do you consume food? (snacks and meals or a beverage without eating). Enter a whole number”, is ambiguous as there is no definition provided for 1 unit of food or beverage. Additionally, since the survey required a whole number response, participants may have rounded their answers, leading to inaccurate data.
  

### Assumptions
The survey collected 50 students’ number of meals, 46 responses range from 2 to 6, however, 4 responses are outliers at 7, 10, 12. It was assumed that these students have special dietary habits or religious purposes that influence meal frequency. 


### Data Cleaning
Command read_csv classifies the columns when the dataset was imported. The column labels were changed from question format to short and precise names for convenience and reusability.


## Research Question 1

Does the amount of caffeine consumed impact an individual's productivity after drinking coffee?

<img width="672" alt="Screenshot 2024-11-22 at 1 05 41 am" src="https://github.com/user-attachments/assets/14bda546-aa26-46af-9150-d97c119cc42d">

<img width="672" alt="Screenshot 2024-11-22 at 1 07 04 am" src="https://github.com/user-attachments/assets/c4f2e265-790b-46e6-a898-88a97f3dd248">


The method used for this question involved the use of two graphs to analyse the correlation between caffeine consumption and productivity. Initially, a box plot was used to depict the difference between caffeine consumption (dependent variable) among individuals with differing past performances (independent variable). 

This plot was seen to be skewed to the right, with a mean surpassing its median. 

For the second graph, responses were categorised into groups based on caffeine levels: non-consumers (0mg), normal consumers (>0mg but <400mg), high consumers (≥400mg), and an overall category encompassing all caffeine consumers. 

These groups were then plotted against mean productivity in an accumulative bar plot, in which the overall mean and correlation coefficient turned out to be 6.15 and 0.48, respectively. 

Furthermore, this graph revealed that high caffeine consumers, though the smallest in quantity, reported the highest average productivity. Conversely, non-consumers, while not the lowest, displayed a lower average productivity compared to the mean. However, this could be a result of the high caffeine consumers’ mean (7.9) skewing the average mean. 

Nonetheless, this suggests a moderate positive correlation between caffeine intake and productivity.


## Research Question 2

What is the relationship between the number of meals students eat and their productivity?

<img width="680" alt="Screenshot 2024-11-22 at 1 08 14 am" src="https://github.com/user-attachments/assets/a9c7b3f7-cd0a-4d27-bd4e-674f92aad46f">

The linear graph displays the relationship between two quantitative variables assessed: The frequency of food consumption per day (including meals, snacks and beverages) and the individual's productivity an hour after eating, measured on a scale of 1 to 10. 

The correlation coefficient (0.3, 2 d.p), suggests a weak, positive correlation between the 2 variables. While there may be a linear trend between the frequency of meals and productivity an hour after eating, the data suggests the relationship may better suit a normal approximation as there was a higher frequency of responses in the middle of the data set and less towards the extremities, in particular the higher values.

<img width="677" alt="Screenshot 2024-11-22 at 1 08 52 am" src="https://github.com/user-attachments/assets/14166aea-f6b9-40ca-993a-fa8a98c20498">

Linear plots have an entirely random distribution of data unlike the residual which shows a symmetrical pattern. As a result, a normal approximation may be a better choice for the model because the data is not well suited for a linear graph, aligning with the models expectations.
