# Bellabeat_Case_Study
### Google Data Analytics course - Capstone Project

# Project Background and Overview
This repository presents a comprehensive data analysis case study of Bellabeat, a pioneering company in women’s wellness technology. As a junior data analyst, I collaborated with Bellabeat’s marketing and executive teams to uncover actionable insights from real-world smart device usage data. The project follows a structured data science workflow-Ask, Prepare, Process, Analyze, Share, and Act-focusing on how activity, sleep, and step-tracking data can inform Bellabeat’s product design and marketing strategies. The analysis showcases my skills in R programming, data cleaning, transformation, and visualization, with the aim of improving user engagement and supporting Bellabeat’s mission to empower women’s health.

# Data Structure Overview
## Data Source
Fitbit Fitness Tracker Data (Kaggle Dataset), collected from 30 users between March and May 2016.
  
  
**Files Used:**

* dailyActivity_merged.csv – daily steps, distance, calories, activity levels

* sleepDay_merged.csv – daily sleep records

* hourlySteps_merged.csv – hourly step counts

**Entity Relationship Diagram (ERD)**

[User] 

  |--< [Daily Activity]
  
  |--< [Sleep Day]
  
  |--< [Hourly Steps]
  
Each user (Id) can have multiple daily activity, sleep, and hourly step records, linked by date.

**Data Preparation**

* Removed duplicates and missing values

* Standardized column names and date/time formats

* Merged datasets for integrated analysis

**Data Limitations**

* Small sample size (30 users)

* No demographic information (e.g., age, gender)

* Data collected via Amazon Mechanical Turk (third-party)

* Data is from 2016 and may not reflect current trends

# Executive Summary
This analysis of smart device data revealed that the majority of users are ‘fairly active’ or ‘lightly active’, with peak activity observed in the late afternoon. There is a moderate positive correlation between daily steps and calories burned, while the relationship between physical activity and sleep duration is weak. These findings highlight opportunities for Bellabeat to increase user engagement through targeted interventions and personalized recommendations.

## Snapshot of Findings:

* 53% of users are ‘fairly active’, 37% are ‘lightly active’

* Peak average steps: 1,200 steps/hour between 5–7 PM

* Steps vs. calories correlation: 0.59

* Steps vs. sleep correlation: -0.13

# Insights Deep Dive
**1. User Activity Segmentation**
Quantified Value: 53% fairly active, 37% lightly active, 10% sedentary or very active

Business Metric: User engagement level

Story: Most users maintain moderate activity, indicating a strong base for engagement but also room to motivate more users toward higher activity levels.

**2. Hourly Activity Patterns**
Quantified Value: Average peak of 1,200 steps/hour between 5–7 PM

Business Metric: Active hours per user

Story: Users are least active in the morning and late evening, with activity spiking after work hours, suggesting optimal times for engagement and notifications.

**3. Steps vs. Calories Burned**
Quantified Value: Correlation coefficient = 0.59

Business Metric: Calorie burn prediction accuracy

Story: Daily steps are a strong predictor of calories burned, supporting the effectiveness of step-based challenges and activity tracking for wellness outcomes.

**4. Sleep vs. Physical Activity**
Quantified Value: Correlation coefficient = -0.13

Business Metric: Sleep quality vs. activity

Story: Physical activity alone does not strongly influence sleep duration, suggesting that Bellabeat should consider additional factors (e.g., stress, hydration) in sleep recommendations.

# Recommendations
* **Personalized Challenges**: Target ‘fairly’ and ‘lightly’ active users with step goals and activity reminders, especially during low-activity hours.

* **Smart Notifications**: Schedule wellness nudges in the app during mornings and late evenings to boost engagement.

* **Holistic Wellness Messaging**: Highlight calorie tracking and balanced activity in marketing materials to attract and retain users.

* **Enhanced Data Collection**: Invest in gathering more recent and diverse user data for richer, more actionable insights.

* **Sleep Guidance**: Integrate additional wellness factors (stress, hydration, mindfulness) into sleep recommendations for a more comprehensive approach.

**Explore the RMarkdown file for detailed code, data cleaning steps, visualizations, and the full analysis process. This project demonstrates my expertise in data analysis, R programming, and the application of data-driven insights to real-world business challenges in the health tech industry.**
