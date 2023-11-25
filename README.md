# Recruitment-Scam-EDA

I conducted an Exploratory Data Analysis (EDA) on a Recruitment Scam dataset sourced from Kaggle ([link](https://www.kaggle.com/datasets/amruthjithrajvr/recruitment-scam/data)). Initially, I examined general information about the dataset, including counts, duplicates, and unique values. Subsequently, I assessed the percentage of null values for each variable. I then proceeded to conduct a similar analysis, but this time, I stratified the dataset based on the explanatory variable, "fraudulent."

Identifying a notable disparity in null percentages between the two classes proved to be insightful. For the "title" variable, I employed word clouds to visualize titles unique to each class. This method was particularly suitable for titles due to their concise nature.

Regarding the "location" variable, I parsed information such as country, state, and city. I examined continents based on class, analyzed countries by fraudulent percentage, and delved into the division within the United States, as it is the primary source of job ads.

After removing HTML tags from textual variables, I explored the distribution of text length across classes. For binary variables, I assessed correlation using a correlation matrix and scrutinized class divisions for the two distinct values.

In the case of categorical variables, I examined the distribution within different values, segmented by classes, and compared it to the overall distribution.

For the "industry" and "function" variables, I sought values unique to each class. Additionally, I explored the top 10 most common values, accounting for null values due to their significant presence and high null percentage.

## Dataset description
1. Title	              - The title of the job ad entry
2. Location             - Geographical location of the job ad
3. Department           - Corporate department (e.g. sales)
4. Salary range         - Indicative salary range (e.g. $50,000-$60,000)
5. Company profile      - A brief company description
6. Description          - The details description of the job ad
7. Requirements         - Enlisted requirements for the job opening
8. Benefits             - Enlisted offered benefits by the employer
9. Telecommuting        - True for telecommuting positions
10. Company logo	      - True if company logo is present
11. Questions           - True if screening questions are present
12. Fraudulent          - Classification attribute
13. In balanced	        - Selected for the balanced dataset
14. Employment type     - Full-type, Part-time, Contract, etc
15. Required experience	- Executive, Entry level, Intern, etc
16. Required education  -	Doctorate, Master’s Degree, Bachelor, etc
17. Industry            - Automotive, IT, Health care, Real estate, etc
18. Function            - Consulting, Engineering, Research, Sales etc
