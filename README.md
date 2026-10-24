# Who Benefits from AI Tools? Usage, Cost, and Productivity Analysis

One-line summary: An analysis of how students and professionals use AI tools, and how usage, cost, and tool choice relate to productivity and satisfaction.

## Project Overview
AI tools are widely used, but it is unclear whether paying for them or using them more leads to better outcomes. This project explores that using survey-style data.

## Research Questions
1. Which AI tools and purposes dominate, and how does this differ between students and professionals?
2. Which tool has the highest satisfaction, accuracy, and productivity scores?
3. Do paid users report higher satisfaction or productivity than free users?
4. Does income influence whether people pay and which tools they choose?
5. How do usage hours and tool choice vary by education level and country?

## Dataset
- **Source:** Kaggle:https://www.kaggle.com/datasets/eishatuzzuhra/ai-usage-and-impact-on-students-and-professionals
- **Size:**  300rows, 19 columns
- **Type:** synthetic data
- **Key columns:** Age, Country, User_Type, Education_Level, Monthly_Income, AI_Tool, AI_Purpose, AI_Usage_Hours_Per_Day, Monthly_AI_Cost, Productivity_Score, Accuracy_Rating, Satisfaction_Score

## Methods
- Cleaned the data (handled missing values, duplicates)
- Exploratory data analysis with pandas, matplotlib, seaborn
- Group comparisons and cross-tabulations


## Key Findings
## Key Findings

*Based on a Kaggle dataset of [N] records; results describe this sample only.*

- **Most popular tool:** ChatGPT is the most used AI tool.
- **Students vs professionals:** Both groups use AI tools in similar proportions, with no major difference in tool or purpose preferences.
- **Gender and income:** Male users report higher average monthly income  than female users in this dataset.
- **Paid vs free satisfaction:** Paid users reported lower average satisfaction  than free users. One possible explanation is that paying raises expectations, but this dataset cannot confirm the reason.
- **Education level:** High school users had the highest average daily AI usage  , though this group is small users.
- **Country:** Users in Canada and Pakistan reported the highest daily usage .

## Visualizations
![Tool usage](![alt text](image-1.png))
![Paid vs free](images/paid_vs_free.png)
![Daily Ai Usage Hours by Country](![alt text](image.png))
![professional vs student](![alt text](image-2.png))
![AI tool and purpose dominate](![alt text](image-3.png))

## Limitations & Disclaimer
## Limitations

- **Data source:** The data comes from a Kaggle dataset. Its collection method is not fully documented, and it may be synthetic or non-representative, so the results should not be generalized to all AI users.
- **Self-reported scores:** Productivity, accuracy, and satisfaction are subjective ratings and may reflect personal bias rather than actual performance.
- **Small sample:** With small records, groups such as high school users and some countries have very few observations. Averages for these groups are unstable, so the results for them are only indicative.
- **Correlation, not causation:** Relationships found here do not show that one factor causes another. For example, lower satisfaction among paid users may reflect higher expectations, but this was not tested.
- **Uncontrolled factors:** Comparisons such as income by gender were not adjusted for country, profession, or education, which may explain part of the gap.
- **Income comparability:** Monthly income may not be standardized across countries, so cross-country comparisons of income are unreliable.
- **Different score scales:** Accuracy, satisfaction, and productivity are measured on different scales, so they should not be compared directly with each other.
- **Snapshot in time:** The data captures one point in time and cannot show how usage or satisfaction changes over time.
- **Cleaning choices:** Decisions on missing values and outliers may have affected the results slightly.

## Tools Used
Python, pandas, numpy, matplotlib, seaborn

## Author
Kiran Pandey, [www.linkedin.com/in/kiran-pandey-96ba79424]

