# Bank Churn Analysis Visualization with Tableau

This project visualizes customer churn data for a fictional bank, analyzing the factors influencing churn in the credit card segment. Using Tableau, this project creates detailed dashboards that provide insights into customer demographics, transaction behaviors, and churn trends. The goal is to enable effective strategies for customer retention and improve the bank’s understanding of customer dynamics.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Data Preparation](#data-preparation)
- [Visualization Dashboards](#visualization-dashboards)
- [Installation](#installation)
- [Usage](#usage)
- [Conclusion and Insights](#conclusion-and-insights)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Bank Churn Analysis project aims to identify factors that contribute to customer churn in the banking industry, focusing on credit card users. Using demographic data, transaction behaviors, and customer engagement metrics, we build a set of dashboards that provide a comprehensive overview of customer segments at risk of churning.

## Dataset

- **Source**: Kaggle’s Credit Card Dataset by Peachji
- **Details**: The dataset includes key features such as:
  - **Attrition Flag**: Customer status (active or churned)
  - **Demographic Data**: Age, gender, marital status, income category, education level
  - **Transaction Metrics**: Total transactions, revolving balance, credit limit
  - **Geographic Data**: Country, province, and city
  - **Account Metrics**: Months active, credit utilization, relationship count

The dataset encompasses customer records across ASEAN countries, allowing for regional insights into churn behavior.

## Technologies Used

- **Tableau**: Primary tool for creating interactive dashboards and visualizing data trends
- **Python (optional)**: For data preprocessing, cleaning, and exporting to Tableau-friendly formats
- **Microsoft Excel**: Basic data handling and organization before uploading to Tableau

## Data Preparation

1. **Data Cleaning**: Removing any inconsistencies, handling missing or invalid values.
2. **Data Transformation**: Converting categorical variables and preparing numerical data.
3. **Feature Engineering**: Creating additional columns for insights, such as average utilization ratios and transaction categories.

## Visualization Dashboards

The project consists of four primary dashboards:

1. **Revenue Reports**:
   - **Objective**: Analyze revenue distribution across ASEAN countries.
   - **Features**: Visualization of revenue by country, transaction categories, and monthly trends.
   - **Insights**: Key revenue drivers and trends over time, useful for identifying high-value regions and customer segments.

2. **Churn Reports**:
   - **Objective**: Visualize customer churn rates and demographics.
   - **Features**: Country-wise churn map, churn demographics, and churn trends.
   - **Insights**: Patterns in customer churn, highlighting at-risk segments by demographics.

3. **Customer Behavior Report**:
   - **Objective**: Explore transaction behaviors by customer generation and card type.
   - **Features**: Breakdown of transaction volume by age group and customer status.
   - **Insights**: Generational differences in banking behavior and preferences.

4. **Utilization Ratio Report**:
   - **Objective**: Display credit utilization patterns by age and geography.
   - **Features**: Geographic utilization map, age-wise utilization trends.
   - **Insights**: High utilization regions and age groups, indicating financial behaviors and potential credit risk.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/FebianFelix/BankChurnAnalysis_VisualizationTableau.git
   ```
2. **Prepare the Dataset**: Download the dataset from Kaggle and save it in the project folder.
3. **Open Tableau**: Use Tableau to connect the dataset and access the predefined dashboards.

## Usage

1. **Open Tableau** and load the dataset.
2. **Access Dashboards**: Explore each dashboard (Revenue, Churn, Customer Behavior, and Utilization Ratio) to analyze customer behavior and churn patterns.
3. **Filter and Drill-Down**: Use Tableau’s filtering and drill-down capabilities to gain deeper insights into specific demographics or geographic regions.

## Conclusion and Insights

The analysis revealed that:
- Younger and lower-income customers tend to have higher churn rates.
- Customers with higher-tier credit cards (Gold, Platinum) are less likely to churn.
- High utilization ratios among middle-aged groups suggest higher credit dependency, which may indicate churn risk if not managed well.

These insights can help banks tailor marketing and retention strategies, focusing on at-risk segments with targeted engagement.

## Contributing

1. **Fork this repository**.
2. **Create a new branch** for your feature or fix (`git checkout -b feature/AmazingFeature`).
3. **Commit your changes** (`git commit -m 'Add AmazingFeature'`).
4. **Push to the branch** (`git push origin feature/AmazingFeature`).
5. **Open a Pull Request**.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
