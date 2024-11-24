# AeroFit Case Study

## Project Overview
This case study explores AeroFit, a fitness company that offers gym memberships and online fitness training. The project involves analyzing customer data to understand usage patterns, customer behavior, and overall fitness trends. The analysis aims to provide actionable insights to improve customer engagement, retention strategies, and overall business performance.

Project link: [AeroFit Case Study](https://github.com/DurgaPrasadsampatirao/DurgaPrasadsampatirao-Aerofit-Data-Analysis.git)

---

## Key Objectives
1. **Customer Segmentation**: Identify different customer segments based on usage patterns, demographics, and preferences.
2. **Retention Analysis**: Analyze customer retention rates and identify key factors influencing member drop-off.
3. **Fitness Program Effectiveness**: Assess the effectiveness of various fitness programs offered by AeroFit and identify areas for improvement.
4. **Revenue Analysis**: Understand revenue generation patterns by analyzing membership plans and additional services purchased by members.
5. **Operational Insights**: Provide actionable insights to optimize operations, improve customer engagement, and enhance business performance.

---

## Insights and Findings

### 1. Data Overview
- **Dataset**: The dataset includes customer information, gym usage data, membership details, and customer feedback.
- **Key Columns**:
  - `customer_id`: Unique identifier for each customer.
  - `age`: Age of the customer.
  - `gender`: Gender of the customer.
  - `membership_type`: Type of membership (e.g., monthly, annual, premium).
  - `visit_frequency`: Frequency of gym visits (e.g., daily, weekly).
  - `fitness_program`: Program chosen by the customer (e.g., weight loss, bodybuilding).
  - `feedback`: Customer feedback on the fitness program (e.g., satisfaction level).
  - `join_date`: Date the customer joined the gym.
  - `renewal_date`: Date the customer renewed their membership.
  - `churn`: Whether the customer has canceled their membership (binary: Yes/No).

### 2. Customer Segmentation
- **Frequent Visitors**: A large segment of customers visit the gym 3-4 times a week, with higher engagement seen in customers enrolled in premium programs.
- **Age-Based Segments**: Customers aged 18-30 tend to opt for group fitness classes, while customers 30+ prefer personal training sessions.
- **Gender Preferences**: Men show more interest in bodybuilding programs, while women lean towards weight loss and general fitness programs.

### 3. Retention Analysis
- **Churn Rate**: Customers with low engagement (e.g., visiting less than once a week) have a higher churn rate.
- **Retention Strategies**: Personalized fitness plans and regular engagement (e.g., fitness challenges, promotions) significantly reduce churn.
- **Program-Specific Retention**: Customers who are enrolled in longer-term fitness programs (e.g., 6-month or yearly plans) tend to stay longer.

### 4. Fitness Program Effectiveness
- **Program Effectiveness**: Weight loss and bodybuilding programs are the most popular, with high satisfaction rates.
- **Improvement Areas**: Programs targeting flexibility and wellness have lower engagement, suggesting a need for program redesign or more targeted marketing.
  
### 5. Revenue Analysis
- **Revenue Generation**: Premium memberships generate the highest revenue, followed by personal training sessions.
- **Service Add-Ons**: Additional services like nutrition counseling and personal training sessions contribute significantly to overall revenue.

---

## Methodology
1. **Data Collection**: The dataset includes customer engagement data collected from the gym's membership system and customer feedback.
2. **Data Cleaning**: Missing values, duplicates, and outliers were handled, ensuring clean data for analysis.
3. **Exploratory Data Analysis (EDA)**: Analyzed customer behavior, gym usage patterns, and revenue trends using visualizations and descriptive statistics.
4. **Segmentation & Clustering**: Applied clustering techniques to segment customers into different groups based on usage patterns, demographics, and program preferences.

---

## Technologies Used
- **Python**: For data cleaning, analysis, and visualization.
- **Libraries**: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn
- **Jupyter Notebooks**: For interactive analysis and visualization.
- **SQL**: For querying customer and membership data from the database.

