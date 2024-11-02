# Titanic Survival Prediction

This project aims to analyze the Titanic dataset to predict passenger survival based on various features. Utilizing machine learning algorithms, the project explores the relationships between passenger characteristics and their survival outcomes.

## Dataset Overview

The dataset used in this analysis includes information about the passengers on the Titanic, with the following columns:

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Fare paid by the passenger.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Data Visualization

The following visualizations were created to explore the dataset and understand the relationships between features and survival:

### 1. Count Plot of Survival Status
A count plot showing the number of survivors and non-survivors.

![Count Plot of Survival Status](count_plot_survival_status.png)

### 2. Bar Plot of Survival by Gender
This plot illustrates the survival rates by gender.

![Bar Plot of Survival by Gender](bar_plot_survival_by_gender.png)

### 3. Box Plot of Age vs. Survival
A box plot comparing the ages of survivors and non-survivors.

![Box Plot of Age vs. Survival](box_plot_age_vs_survival.png)

### 4. Count Plot of Survival by Passenger Class
This count plot shows the number of survivors and non-survivors across different passenger classes.

![Count Plot of Survival by Passenger Class](count_plot_passenger_class.png)

### 5. Violin Plot of Fare vs. Survival
A violin plot showing the distribution of fare prices for survivors and non-survivors.

![Violin Plot of Fare vs. Survival](violin_plot_fare_vs_survival.png)

### 6. Heatmap of Correlation
A heatmap representing the correlation between various features in the dataset, highlighting the relationships between age, fare, class, and survival status.

![Heatmap of Correlation](heatmap_correlation.png)

## Requirements

To run this project, ensure you have the following libraries installed:

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn (for machine learning model)

You can install the required libraries using pip:

```bash
pip install pandas seaborn matplotlib scikit-learn
```

## Usage

1. Load the dataset into your environment.
2. Preprocess the data, including handling missing values.
3. Generate visualizations to explore relationships within the data.
4. Implement machine learning algorithms to predict survival outcomes based on the features.

## Conclusion

This project provides insights into the factors influencing passenger survival on the Titanic. By analyzing the relationships between different features, we can better understand which characteristics may have impacted survival chances.
