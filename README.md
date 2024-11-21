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







