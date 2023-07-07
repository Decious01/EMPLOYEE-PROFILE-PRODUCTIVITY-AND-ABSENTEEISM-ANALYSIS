![image.png](attachment:image.png)

# EMPLOYEE-PROFILE-PRODUCTIVITY-AND-ABSENTEEISM-ANALYSIS
### INTRODUCTION:
This Human Resources data analysis project aims to identify patterns and reasons for employee absenteeism and productivity within an organization. This project uses data obtained from Explore Data science Academy for project purposes which includes employee records, time and attendance logs, and performance evaluations, to analyze the causes and effects of absenteeism and productivity.

Power BI Data visualization tool was used to create interactive dashboards and reports on identified trends, patterns to communicate insights to stakeholders and decision-makers.

This project aims to provide actionable insights that can be used to improve employee engagement, reduce absenteeism rates, and increase productivity within the organization. The findings and recommendations from this project will inform HR policies and practices and can be used to make data-driven decisions for the betterment of the organization.

### DATA INFORMATION:

The project begins with a thorough data cleaning and preparation process to ensure the data is accurate and reliable. 

The data consists of two tables which are the Employee Information Table and the Abseentism Table.
Information in the Employee table includes 11 features and 37 rows containing the following Information:

-ID Unique identifier for each employee.

-Transportation expense Transportation cost (in USD).

-Distance from residence to work The distance from the place of work and the employee’s place of
residence (kilometres).

-Age of the employee (years).

-Education High school (1), graduate (2), postgraduate (3), master and doctor (4).

-Children Number of child dependents.

-Social drinker Either “yes” (1) or “no” (0).

-Social smoker Either “yes” (1) or “no” (0).

-Pet The number of pets an employee has.

-Weight The weight of the employee (in kilograms).

-Height The height of the employee (in centimetres).

Information in the Absenteeism Table includes 639 rows and 9 features containing the following Information:

-ID: Unique identifier for each employee.

-Reason for absence:

Code 0- Incomplete submission

Code 1, 2, 3, and 4- Family-related

Code 5 – 25, 27, 28-Medical reasons

Code 26-Unjustified leave

-Month of absence: Month number of the year.

-Day of the week: Monday (2), Tuesday (3), Wednesday (4), Thursday (5), Friday (6).

-Work load Average/day: Average number of work tasks completed per day.

-Work Load Range(Calculated Column):
 Light Workload(Less than 250)

    Medium Light Workload(250-300)

    Medium Workload(300-350)
    
    Heavy Workload(Above 350)
    
-Hit target: Target hit factor (0–100)

-Productivity(Calculated Column):

    Hit target(95-100=Excellent)

    Hit target(90-95=Very Good)
    
    Hit target(85-90= Good)

    Hit target(Less than 85=fair)

-Disciplinary failure: A failure to adhere to a previous disciplinary warning relating
 to absenteeism (yes=1, no=0).

-Absenteeism time in hours: Number of hours the employee has been absent.

-Service time: Number of working hours produced by each employee.

### OBSERVATIONS
#### Reasons for Abseentism:

Observation 1: Prevalence of Medical Reasons for Absenteeism

Upon analyzing the data, it was observed that medical reasons accounted for over 90% of the reported causes of employee absenteeism. This finding suggests that health-related issues significantly impact the workforce's ability to attend work regularly. These medical reasons might range from acute illnesses to chronic conditions or recurring health concerns.

Observation 2: Incomplete Submission as a Secondary Reason

The second most common reason cited for absenteeism was "Incomplete submission." While the data does not provide specific details about this category, it implies that employees were absent due to unfinished tasks, projects, or deliverables. It is important to further investigate this reason to understand its underlying causes and potential solutions.

Observation 3: Family Related Issues as a Minor Contributor

Among the reported reasons for absenteeism, "family related issues" appeared to be the least prevalent. While this observation suggests that family-related matters play a relatively minor role in employee absenteeism, it is worth exploring this category further to understand the specific challenges employees might face in this context.

#### Seasonal, Monthly and Weekly Absenteeism Patterns

Observation 1: Seasonal Absenteeism Patterns
It was observed that the highest period of absenteeism occurred during the spring season, accounting for 30% of total absences. The summer period followed with 24% of absences, while autumn and winter had lower absenteeism rates. This finding suggests a potential correlation between specific seasons and employee absenteeism.

Observation 2: Monthly Absenteeism Patterns

Further analysis revealed that the highest month of absenteeism was March. It is important to investigate the reasons behind this peak, as it may be influenced by various factors such as seasonal illnesses, allergies, or other external factors specific to that particular month.

Observation 3: Day of the Week Absenteeism Patterns

When examining the days of the week, it was observed that Tuesday had the highest rate of absenteeism. This finding suggests that there may be factors specific to Tuesdays that contribute to employee absences, such as recurring medical appointments or personal issues.

#### Health Patterns:

Observation 1: Smoking Habits

While analyzing the data, it was observed that 58% of the workforce are smokers, while 42% are non-smokers. This finding highlights a significant proportion of employees engaging in smoking behavior.Smoking can have detrimental effects on health, leading to various diseases and potentially impacting absenteeism rates, as well as overall productivity and well-being in the workplace.

Observation 2: Alcohol Consumption

The analysis also revealed that 20% of employees are social drinkers, while the remaining 80% do not consume alcohol. This observation indicates that a minority of the workforce engages in social drinking. While moderate alcohol consumption is not necessarily harmful, excessive or frequent drinking can have adverse health effects and potentially impact work performance and attendance.

Observation 3: Distribution of BMI Categories

Analyzing the BMI index of the workforce, it was observed that 65% fall within the normal range. This finding suggests a relatively healthy workforce in terms of weight management. Additionally, 7% of employees are classified as overweight, 2% as obese, and 1% as underweight. These figures indicate the distribution of weight-related categories within the organization.


#### Productivity & Workload Distribution:

Observation 1: Productivity Levels

It was observed that 49% of employees were rated as having excellent productivity, while 42% had very good productivity. Additionally, 5% of employees were rated as good, and 3% were considered to have fair productivity. These findings suggest a predominantly high level of productivity among the workforce, with a relatively small percentage falling below the very good rating.

Observation 2: Workload Distribution

The analysis also revealed the distribution of workload levels within the organization. It was observed that 43% of employees had a medium-light workload, while 38% had a light workload. Furthermore, 16% of employees had a medium workload, and only 3% had a heavy workload. These findings indicate that the majority of employees have relatively manageable workloads, with a small percentage experiencing heavy workloads.

Observation 3: Correlation Between Productivity and Workload Distribution

It was observed that employees with the medium light workload have the highest productivity levels in the company. This susggests that priority should be given to ensure adequate workdistribution amongst the eployees to specifically fall within this range in order to enjoy the highest returns on productivity.

#### Productivity & Employee Commuting Distance:
Observation 1: Commuting Distance Distribution
Analysis revealed the distribution of employee commuting distances. It was observed that 35% of employees lived within a range of 10-20km from work, while 27% lived 20-30km away. Additionally, 16% lived 40-50km away, 8% lived beyond 50km, 8% lived 30-40km away, and less than 5% lived within a 10km radius of the workplace.

Observation 2: Proximity and Productivity
It was observed that a small percentage of employees live within a 10km radius of the workplace. This suggests that proximity to the workplace may not have a direct correlation with productivity. Excellent and very good productivity levels were observed across various commuting distance categories, indicating that factors beyond proximity influence employee performance.

### RECOMMENDATIONS

#### Health:
Given that the majority of reported absences are attributed to medical reasons, despite the seemingly healthy BMI index, it is evident that other factors may be contributing to the high rate of absenteeism. Possible areas of further investigation could include:

Work Environment: Assessing the workplace conditions, such as ergonomic factors, stress levels, or job satisfaction, to determine if they contribute to employees' health issues and subsequent absenteeism.

Sick Leave Policies: Reviewing the organization's sick leave policies to determine if they adequately support employees' medical needs and whether any adjustments or improvements are necessary.

Individual Health Assessments: Conducting individual health assessments or surveys to gain a more comprehensive understanding of employees' health statuses, including underlying medical conditions and lifestyle factors.

Smoking Cessation Programs: Given the high percentage of smokers, implementing smoking cessation programs or providing resources for employees to quit smoking could significantly improve the overall health and well-being of the workforce.

Alcohol Awareness Initiatives: While a minority of employees are social drinkers, promoting responsible alcohol consumption through education and awareness initiatives can help ensure a healthy work environment and prevent any potential negative consequences associated with excessive drinking.

Healthy Lifestyle Promotion: Building initiatives around healthy eating, physical activity, and stress management can contribute to maintaining a normal BMI and reducing the prevalence of overweight and obesity among employees. These programs can be tailored to individual needs and offer support for sustainable lifestyle changes.
Wellness Programs and Resources: Offering comprehensive wellness programs, including access to fitness facilities, nutritional counseling, and mental health support, can further encourage employees to adopt healthy habits and improve their overall well-being.

#### Seasonal, Monthly and Weekly Absenteeism Patterns:
Seasonal Factors: Identifying the specific reasons for increased absenteeism during spring and summer seasons can help organizations implement preventive measures, such as promoting health and wellness initiatives, encouraging flu vaccinations, or addressing any workplace factors that may contribute to seasonal absences.

March Absenteeism: Investigating the reasons behind the high absenteeism in March can provide insights into potential factors such as seasonal illnesses, flu outbreaks, or other external events that may influence employee attendance. Targeted interventions or proactive measures can then be implemented to address any underlying issues.

Tuesday Absenteeism: Understanding the reasons for the high absenteeism rate on Tuesdays is crucial for identifying any recurring patterns or specific factors affecting employee availability. Organizations can explore flexibility in scheduling or adjust workloads to accommodate potential personal obligations that may arise on this day.

Documentation and Employee Surveys: Collecting additional data through documentation or surveys can help uncover the specific reasons behind the observed patterns. Gathering information about the nature of absences, employee feedback, or specific events coinciding with periods of high absenteeism can provide valuable insights for organizational interventions.

#### Productivity Levels, Workload Distribution & Commuting Distance:
Recognizing and Rewarding Excellent Productivity: With nearly half of the employees demonstrating excellent productivity, organizations can acknowledge and reward these high-performing individuals. Recognitions such as incentives, promotions, or additional responsibilities can help motivate and retain top performers.

Balancing Workload Distribution: The distribution of workload levels indicates that a significant percentage of employees have manageable workloads. However, attention should be given to the small percentage with heavy workloads to prevent burnout and ensure sustained productivity. Organizations can consider redistributing workload, optimizing resource allocation, or implementing workload management strategies to maintain a healthy balance.

Continuous Performance Evaluation: Regularly evaluating employee productivity and workload levels allows organizations to identify trends and make informed decisions. Performance evaluations can help identify strengths and areas for improvement, enabling targeted training and development initiatives to enhance overall productivity.

Impact of Commuting Distance: While no direct correlation was established between productivity and commuting distance, it is important to recognize that long commuting distances may contribute to employee stress, fatigue, or time constraints. Organizations should consider providing support mechanisms, such as flexible working hours, remote work options, or transportation assistance, to alleviate potential negative effects of long commutes on employee well-being.

Work-Life Balance: Understanding the distribution of commuting distances can help organizations address work-life balance concerns. By identifying employees with longer commutes, organizations can explore initiatives to enhance work-life integration, promote employee well-being, and optimize productivity.

### CONCLUSION

The project provided valuable insights into multiple aspects of employee performance, well-being, and organizational efficiency. By understanding absenteeism reasons, patterns, productivity levels, workload distribution, and commuting distances, organizations can implement targeted strategies to improve employee well-being, optimize productivity, and foster a positive work environment.




