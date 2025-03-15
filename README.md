# Data-Analysis-and-Prediction-for-the-Paris-Olympics
Below is a GitHub README file in Markdown format based on your Business Data Analytics project assignment for CDS504. It provides a concise yet comprehensive overview of the project, including its objectives, team details, methods, findings, and more, tailored for a GitHub audience.

---

# Paris Olympics Data Analysis and Prediction

This project analyzes the Paris 2024 Olympics dataset to explore the relationship between athletes' age, nationality, and medal awards, as well as the performance and medal distribution of various countries. Using advanced data analytics and machine learning techniques, we aim to provide actionable insights for sports managers and policymakers to optimize athlete selection, training, and participation strategies. Additionally, we predict medal counts for the 2028 Los Angeles Olympics.

## Project Background

The Olympic Games serve as a global stage for showcasing athletic excellence and national pride. By leveraging Olympic data, this project uncovers patterns in athlete performance and medal distribution to inform evidence-based sports development strategies. Focusing on the Paris 2024 dataset, we provide insights into age-related performance trends, national medal dominance, and predictive modeling for future games.

## Data Sources

Our analysis is based on the following datasets:

- **Medals_total**: Nominal data (country) and numerical data (gold, silver, bronze, total medals).
- **Medals**: Nominal data (medal type, gender, discipline, country).
- **Athletes**: Nominal data (country, discipline, birth country, birth place) and numerical data (birth date).
- **Total_medal_1896_2024**: Historical medal data (1896–2024), including edition, country, and medal counts.

## Analysis Methods

We employed a range of data analytics techniques:

- **Group Comparison**: Compared medal distributions across age groups.
- **Visualization Charts**: Used bar and pie charts to illustrate medal distributions by country.
- **Comparative Analysis**: Analyzed medal wins by country across different sports.
- **Trend Analysis**: Visualized medal count trends over time with trend graphs.
- **Machine Learning Models**:
  - **Random Forest**: Predicted medal likelihood and identified key factors.
  - **Linear Regression**: Provided baseline predictions for medal counts.
  - **Decision Tree**: Analyzed factors influencing medal distribution.

## Key Findings

- **Age and Performance**: Most medal winners fall in the 24-29 age group, suggesting this as the peak competitive age.
- **National Dominance**: The USA and China lead the medal tally, with developed countries and Permanent Five members (excluding Russia) performing strongly.
- **Economic Correlation**: A country’s economic strength correlates with its sports performance.
- **Regional Disparities in China**: Variations in medal counts across Chinese provinces may reflect differences in sports resources, culture, and training systems.

## Prediction Models

We developed models to forecast medal counts for the 2028 Los Angeles Olympics:

- **Random Forest**: Delivered reliable predictions with minimal deviation (MAE: ~4-7 medals, R²: 0.82-0.86) and no overfitting, making it our top-performing model.
- **Linear Regression**: Served as a baseline with moderate accuracy (MAE: ~6 medals, R²: 0.67-0.71).
- **Decision Tree**: Achieved high accuracy (R²: ~1.0) but showed signs of overfitting.

**Special Insight**: The "host country effect" suggests the USA may exceed predictions (120-130 medals or more) in 2028 due to hosting advantages, as observed in past Olympics (e.g., Japan 2020, France 2024).

## Data Visualization

Using Tableau, we created interactive dashboards to visualize:

- Medal distribution by country.
- Medal trends by age group and gender.
- Medal distribution across Chinese provinces.
- Historical medal trends (2000–2024).
