
# Predicting Human Migration using Machine Learning

This project applies machine learning to predict human migration patterns between countries using historical migration data. It demonstrates data preprocessing, model building, evaluation, and visual analysis of migration trends.

## 🔍 Problem Statement

Human migration is an important topic for urban planning, public policy, and international cooperation. The goal is to predict the number of migrations based on features like country of origin, citizenship, year, and migration type (Arrival, Departure, Net).

## 📁 Dataset

The dataset `migration_nz.csv` contains the following columns:

- `Country`
- `Citizenship`
- `Measure` (Arrivals, Departures, Net)
- `Year`
- `Value` (Number of migrants)

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn (RandomForestRegressor, train_test_split)

## 📊 Workflow

1. **Data Preprocessing**
   - Handled categorical variables using `factorize()`
   - Converted `Measure` strings to numeric values
   - Filled missing values with median
   - Dropped non-numeric columns

2. **Feature Engineering**
   - Created numeric columns: `CountryID`, `CitID`
   - Selected features: `CountryID`, `Measure`, `Year`, `CitID`

3. **Model Building**
   - Applied `RandomForestRegressor` from `scikit-learn`
   - Used a 70-30 train-test split
   - Evaluated model using R² score

4. **Visualization**
   - Trend of total migration by year (line plot and bar plot)
   - Correlation heatmap of all numeric fields

## 📈 Results

- Achieved an R² score of approximately **0.73** with Random Forest Regressor.
- Visualized how migration changed over time and explored feature correlations.

## 📌 Note

This project was completed during college as part of a self-learning effort in applied machine learning.  
Maintained by **udita2404**.

## 📫 Contact

Feel free to connect:

- GitHub: [udita2404](https://github.com/udita2404)
- Instagram: [@uditaaa_24](https://www.instagram.com/uditaaa_24)
