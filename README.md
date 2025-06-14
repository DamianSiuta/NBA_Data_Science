# NBA Data Science Project: What Decides Victory?

## Project Overview
This project analyzes NBA game data to determine which factors most influence the outcome of a game. Using historical match statistics and machine learning models, we explore how team performance metrics relate to winning or losing.

## Dataset
The dataset contains NBA regular-season games with detailed stats for home and away teams, including points scored, shooting percentages, assists, rebounds, and more.

## Steps performed
1. **Data Cleaning and Preparation**  
   - Handling missing values  
   - Selecting relevant features  
   - Creating target variable (home team win: 1 or 0)  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizations: correlation heatmaps, boxplots  
   - Comparing stats between winners and losers  

3. **Feature Engineering**  
   - Feature selection based on importance and correlation  
   - Splitting dataset into training and test sets  

4. **Modeling**  
   - Logistic Regression and Random Forest classifiers  
   - Model training and evaluation (accuracy, confusion matrix, classification report)  

5. **Feature Importance Visualization**  
   - Analyzing which statistics most influence the model predictions  

6. **Time Series Analysis (Bonus)**  
   - Investigating how feature importance changes across seasons  

## Results
- The Random Forest model achieved high accuracy (~98%).  
- Points scored by both home and away teams, and shooting percentages were among the most important features for predicting game outcome.

## How to Run
1. Clone the repo  
2. Install dependencies: `pip install -r requirements.txt` (if you create this file)  
3. Download the dataset from [link to dataset] and place it in the project folder  
4. Run the Jupyter Notebook `nba_analysis.ipynb`

## Technologies Used
- Python 3.x  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- Jupyter Notebook  

## Author
Damian Siuta  
[GitHub](https://github.com/DamianSiuta) | [LinkedIn](https://www.linkedin.com/in/damiansiuta)

---

If you want, I can help you prepare also a short LinkedIn post or summary to promote your project there!
