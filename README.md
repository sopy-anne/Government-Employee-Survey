# Government-Employee-Survey
## Introduction

Data plays a crucial role in providing facts that guide strategic decision-making. This project explores a U.S. government employee survey conducted by Pierce County, WA, which assessed employees’ knowledge of their job roles, job satisfaction, opportunities for growth, and inclusion within their departments. 

The survey was based on a five-point scale ranging from 0 (not applicable) to 4 (strongly agree), with responses collected from approximately 14,710–14,725 participants. The dataset included key demographic information such as role identification (staff, supervisor, manager, or director) and departmental details, along with responses to ten core job satisfaction questions. 
### Survey Questions
1. I know what is expected of me at work.
2. At work, I have the opportunity to do what I do best every day.
3. In the last seven days, I have received recognition or praise for doing good work.
4. My supervisor or someone at work seems to care about me as a person.
5. The mission or purpose of our organization makes me feel my job is important.
6. I have a best friend at work.
7. This past year, I have had opportunities at work to learn and grow.
8. My supervisor holds employees accountable for performance.
9. My department is inclusive and demonstrates support for a diverse workforce.
10. Overall, I am satisfied with my job.

### Key Research Questions 
1. How did the employees respond to the survey?
2. What is the response pattern? 
3. Which survey questions did respondents agree with or disagree with most? 
4. Are there any patterns or trends by departments or roles? 

## Data Preparation and Analysis
Data cleaning and preparation were conducted in Power Query Editor (Power BI). The following steps were taken:
- Replaced null values and corrected spelling inconsistencies
- Standardized column names and separated question numbers from question texts
- Applied DAX functions to create calculated columns, totals, and average response measures

## Visualization and Dashboard
A pie chart was used for the role composition across respondents
A stacked bar chart was used for the distribution of roles across departments
A line chart was used for the Average response trends across departments
A column bar chart was used to compare survey questions based on average responses 

Here is the Dashboard summarizing the insights 

![](https://github.com/sopy-anne/Government-Employee-Survey/blob/main/Screenshot%202025-09-28%20233321.png)
## Key Insights

### 1. Demographics
- Only 21 departments participated in the Survey
- Role Indication: 72% of respondents did not specify their role, making them the majority across departments. Notably, respondents from the Medical Examiner and Family Justice Center did not indicate their roles at all.
- Among those who identified roles: 11% Supervisors, 8% Staff, 7% Managers, and 1% Directors.

### 2. Response Patterns

- The Average response was 2.98.
- The majority of responses were positive, with Agree (40%) and Strongly Agree (36%) accounting for over three-quarters of all responses.
- Negative responses were smaller but notable: Disagree (15%), Strongly Disagree (7%), and Not Applicable (3%).

### 3. Question-Level Insights

- Highest-rated question: Question 1 “I know what is expected of me at work” with an average score of 3.5, suggesting strong role clarity.
- Lowest-rated question: Question 6, “I have a best friend at work”, with an average score of 2.6, indicating weaker social connectedness.
- Question 3, "In the last seven days, I have received recognition or praise for doing good work", also scored below average, highlighting room for improvement in employee appreciation.

### 4. Department-Level Insights

- The Sheriff’s Department reported the lowest average responses across most questions, with only Question 1 (role clarity) above the overall average (3.3). Recognition (Question 3) was especially low, averaging 1.9.
- Across departments, Question 8 (Supervisor accountability) consistently scored below the overall average, suggesting a broader issue with performance management practices.

You can view the interactive dashboard here: https://github.com/sopy-anne/Government-Employee-Survey/blob/main/Employee%20Survey%20Dashboard.pbix
## Recommendations and Conclusion 

The analysis suggests several areas for improvement. Government agencies should continue to reinforce role clarity, as this is a significant driver of employee satisfaction. At the same time, recognition programs need to be improved so that employees feel appreciated for their work on a more frequent basis. Employers should also create more opportunities for professional growth and development through training, mentorship, and career progression pathways. Strengthening accountability structures among supervisors is another key priority, ensuring that performance is monitored and managed effectively. Finally, inclusivity efforts should be scaled up, with targeted interventions in departments where support for inclusivity and diversity is weaker.


### Connect with me on LinkedIn: 
www.linkedin.com/in/sopuluchukwu-ugwu
