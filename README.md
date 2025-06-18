## Project Overview

The sinking of the RMS Titanic remains one of history's most infamous maritime disasters. By analyzing the Titanic dataset, this project seeks to uncover which socio-economic and demographic features most strongly affected survival odds. The analysis proceeds from data cleaning and EDA through feature engineering and concludes with predictive modeling.


## Dataset

- **Original data source:**  
  [Kaggle: Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset?select=Titanic-Dataset.csv)

The dataset includes passenger information such as age, sex, ticket class, fare, cabin, and whether the passenger survived.


## Project Structure

- `Titanic EDA.ipynb` — Jupyter notebook with the full workflow (EDA, feature engineering, modeling)
- `titanic_cleaned.csv` — Cleaned Titanic dataset after preprocessing
- `titanic_features.csv` — Feature-engineered dataset ready for modeling
- `.gitignore` — Excludes large or raw data files from version control


## Exploratory Data Analysis

The EDA section of the notebook includes:
- Visualizations of survival rates by gender, age, class, and family size
- Distribution plots for continuous features (e.g., fare, age)
- Analysis of missing data and imputation strategies
- Insights into ticket prices, cabin locations, and embarkation points


## Feature Engineering

Key feature engineering steps:
- Creating new features (e.g., family size, title extraction from names)
- Encoding categorical variables (e.g., sex, embarkation point)
- Handling missing values using imputation
- Scaling or normalizing continuous features


## Modeling

The project builds and evaluates five predictive models:
1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosted Classifier
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors Classifier

Model performance is assessed using accuracy, precision, recall, and F1-score. Feature importance is also analyzed to interpret the results.


## Results

- In-depth analysis of what features most influenced passenger survival
- Visualizations illustrating socio-economic disparities and survival rates
- Comparative model results and discussion of predictive performance


## License

This project is open-source and available under the MIT License.


**View the notebook:**  
[nbviewer link](https://nbviewer.org/github/FletcherMorgan/Titanic-EDA/blob/main/Titanic%20EDA.ipynb)

**Original data source:**  
[Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset?select=Titanic-Dataset.csv)
