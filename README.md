# Workforce Analytics
#### _Unveiling insights to foster workforce sustainability and development_


## Introduction
Maintaining a skilled and satisfied workforce is crucial for any organization aiming for long-term success. With rising competition for talent and increasing employee expectations, organizations must continuously evolve their understanding of employee demographics, compensation, and satisfaction. 

In this project, we use exploratory data analysis techniques in R to uncover insights into the company's compensation practices, workforce diversity, and demographic structure. The analysis will be helpful in identifying disparities and opportunities within the company's workforce demographics and can guide strategic HR decisions such as targeted diversity, equity, and inclusion (DE&I) efforts, recruitment planning, and resource allocation.

## Problem Statement
A Human Resources manager is concerned about various aspects of the workforce, including compensation equity, age distribution, and potential departmental imbalances. They need insights into these areas to develop effective strategies for talent retention, equitable pay scales, and balanced department growth.

## Data Description
- Mock employee level dataset developed by Aaron Rodriguez
- The dataset contains information on employees within an organization.
- The dataset is at EmployeeID level and contains 1,000 rows and 14 columns.
- Includes numeric, categorical, factor and date data types.
- No missing values were reported in the dataset, indicating completeness and reliability for analysis.
- Includes diverse metrics such as age, gender, salary, bonuses, departmental roles, job levels, and city locations.

## Exploratory Data Analysis
Focused on histograms, boxplots and correlation plots for numerical variables, barcharts for categorical variables, and line charts for date. Below are a few observations from the analysis.


##### _Histograms_
 - Histograms provided insights into the distribution of key numerical attributes such as `salary`, `bonus`, and `age` within the workforce.
 - The `salary` histogram reveals a multimodal distribution, suggesting the existence of distinct salary bands, which could correspond to various job grades or levels within the organization. Most employees are concentrated in the lower to middle salary brackets, with a few outliers receiving significantly higher salaries.
 - The `bonus` histogram is notably right-skewed, indicating that a majority of employees receive lower bonuses, with fewer instances of very high bonuses.
 - The `age` histogram displays a distribution that is approximately normal but slightly skewed towards younger employees, indicating a youthful workforce. 


![image](https://github.com/isabhinav/HRExploration1/assets/130937665/8e6ca686-6ea8-4b3a-92e7-c9a2adf96c77)


##### _Boxplots_
 - Boxplots facilitated the detection of distribution disparities and outliers.
 - Notable outliers in `salary` boxplot suggest that a small number of employees have salaries significantly above the rest.
 - The `bonus` boxplot shows a similar pattern to salary, with most bonuses clustering at the lower end and some outliers indicating exceptionally high bonuses.
 - The `age` boxplot presents a relatively symmetrical distribution, indicating a balanced age range across the workforce. 
 

![image](https://github.com/isabhinav/HRExploration1/assets/130937665/dec37102-1bab-48ee-be23-3c6681b39e14)



##### _Correlation Plots_
 - Correlation plot served as a powerful visual tool to understand the relationships between various numerical attributes within the employee dataset.
 - There is a strong positive correlation between `levelnumber` and `salary` (0.91), as well as `salary` and `bonus` (0.94), indicating that as employees ascend through the company levels, both their salary and bonus tend to increase proportionally.
 - Similarly, `levelnumber` and `bonus` show a high correlation (0.88), further supporting the notion that bonuses are likely tied to the hierarchical position within the organization.
 - The correlation between `age` and other numerical factors such as `salary` and `bonus` is comparatively lower, suggesting that age may not be a primary determinant of salary and bonus within this company.


![image](https://github.com/isabhinav/HRExploration1/assets/130937665/248c792d-858d-430c-b5be-fd6f3074417b)


##### _Bar Charts_
- Bar charts used to offer a visual representation of the distribution across categorical variables in the dataset.
- The `gender` distribution bar chart depicts a nearly balanced workforce.
- In the `race` distribution, one group significantly outnumbers the others, highlighting a potential area for the company to enhance racial and ethnic diversity.
- The `department` bar chart shows a relatively even distribution of employees across different organizational functions, without any single department dominating in size.
- The `level` distribution illustrates a hierarchical structure with the highest number of employees at the 'Entry Level' and progressively fewer individuals as the level increases.
- The `city` distribution indicates that the majority of employees are based in a particular city (San Francisco).


![image](https://github.com/isabhinav/HRExploration1/assets/130937665/02702498-0065-45bd-b0a5-0b79d4e3776b)


##### _Related to Date_
- The analysis of employee start dates has yielded several valuable insights into the hiring patterns and tenure at the company, presented through various time-based charts.
- Employee Tenure Distribution: The histogram of employee tenure shows a fairly uniform distribution with a slight decrease as tenure increases. This suggests a steady rate of retention for the first several years, with a gradual drop-off that could be attributed to career progression, external opportunities, or retirement.
- Seasonality in Hiring: A bar chart depicting the number of hires per month indicates clear seasonality in hiring practices. Certain months show a higher number of hires which may align with the company's fiscal calendar, graduate hiring cycles, or seasonal industry demands.
- Trend of Hiring Over Time: A line chart illustrates the trend of hiring over time. 


![image](https://github.com/isabhinav/HRExploration1/assets/130937665/8736622f-a6b4-443a-8fc1-4bc7b14d3212)

![image](https://github.com/isabhinav/HRExploration1/assets/130937665/198480b2-b1e3-4bb9-bf26-11690d73f20f)

![image](https://github.com/isabhinav/HRExploration1/assets/130937665/3b655b7d-1340-4707-80ec-07041948c38f)



## Observations and Takeaways
- Compensation Structure: The analysis seems to indicate a structured compensation system with delineation across job levels. The multimodal distribution of salaries and the strong correlation between salary, bonus, and level number suggest that compensation is tightly coupled with the hierarchical position within the company. 

- Age Distribution: The skew towards younger employees could point to robust junior-level recruitment or a gap in attracting or retaining more experienced professionals. This demographic structure could impact the company's strategic planning. Initiatives such as flexible work arrangements and mentorship programs could be effective in attracting and retaining a more youthful workforce.

- Diversity and Inclusion: While the gender distribution appears balanced, the race distribution highlights a significant opportunity for the company to bolster its diversity initiatives. 

- Hiring Seasonality: The clear seasonality in hiring suggests that recruitment efforts are likely driven by strategic business cycles, project demands, and graduate influxes. Understanding the seasonality in hiring and its underlying causes (e.g., end of fiscal year budget allocations, commencement of major projects, or periods following graduation ceremonies) can help forecast future hiring needs (quantity and types of roles) that will be needed during these peak hiring periods.

- Organizational Structure: The even distribution across departments suggests an equitable allocation of resources, while the level distribution aligns with typical organizational hierarchies, with more entry-level positions and fewer higher-level roles.


## Next Steps
- Compensation Review: Conduct a deeper analysis of the compensation data to ensure equitable pay practices across all demographics, including gender, race, and age. Benchmarking against industry standards could provide additional insights into the company's competitive positioning in the talent market.

- Diversity Initiatives: Develop targeted recruitment and development programs to enhance diversity, particularly in racial and ethnic representation. 

- Recruitment Planning: Leverage the insights from hiring seasonality to streamline the recruitment process. 

- Geographic Spread: Assess the implications of the geographic employee distribution on operational and strategic goals.

Our exploratory analysis reveals a multifaceted view of the company's workforce, with insights that are crucial for fostering an equitable, diverse, and balanced work environment. The analysis presented here lays the groundwork for deeper exploration and data-driven HR decisions.










