# Activity 1 – Student Marks Prediction using Multiple Linear Regression

## Student Details
- **Name:** Rudrapratap Therokar
- **Roll No.:** AD3343
- **Class:** AIDS C
- **Subject:** Regression and Classification Algorithms (CIE 2)
- **Submission GitHub ID:** https://github.com/complexiota
- **PROJECT GITHUB LINK:** https://github.com/ftw-rudra/RCA-Activity-1-AD-3343-


## Objective
To build a Multiple Linear Regression model that predicts student marks using study hours and attendance.

## Dataset
The file `student_marks_prediction_dataset.csv` contains **50 synthetic records** and three columns:

| Column | Description |
|---|---|
| `Study_Hours` | Number of hours spent studying |
| `Attendance` | Attendance percentage |
| `Marks` | Student marks (target variable) |

**Note:** This is an artificially generated dataset for educational practice. It does not contain real student records and should not be used for actual academic decisions.

## Files in This Repository
- `Activity_1_Student_Marks_Multiple_Linear_Regression.ipynb` – Jupyter/Google Colab notebook containing the implementation and analysis.
- `student_marks_prediction_dataset.csv` – Dataset used by the notebook.
- `README.md` – Project information and instructions.

## Work Completed
1. Imported the required Python libraries and loaded the dataset.
2. Checked the dataset structure, data types, summary statistics, missing values and duplicate rows.
3. Selected `Study_Hours` and `Attendance` as input features and `Marks` as the target.
4. Visualized feature relationships using scatter plots, pair plots and a correlation heatmap.
5. Demonstrated the multiple linear regression calculation manually and checked it using Scikit-learn.
6. Split the data into training and testing sets using an 80:20 ratio.
7. Trained and compared single-feature and multiple-feature Linear Regression models.
8. Displayed the regression equation and interpreted the coefficients.
9. Evaluated predictions using MAE, MSE, RMSE and R-squared.
10. Examined residuals, predicted-versus-actual values, feature correlation and VIF.
11. Used the trained model to predict marks for a sample student with 5 study hours and 85% attendance.

## Tools and Libraries
- Python
- Google Colab / Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## How to Run
1. Download or clone this repository.
2. Open `Activity_1_Student_Marks_Multiple_Linear_Regression.ipynb` in Google Colab or Jupyter Notebook.
3. Upload `student_marks_prediction_dataset.csv` to the notebook environment.
4. Run the notebook cells from top to bottom.

## Key Learning Outcomes
- Understand the basic working of Multiple Linear Regression.
- Identify input features and a continuous target variable.
- Train and test a regression model.
- Interpret regression coefficients and the regression equation.
- Evaluate model performance using regression metrics and diagnostic plots.
- Generate a prediction for a new example.

## Limitations
- The dataset is small and synthetic.
- Results are intended for learning and demonstration only.
- Linear Regression assumptions should be checked using the diagnostic plots and VIF; they should not be assumed to hold automatically.
- The model does not establish that study hours or attendance cause a particular mark.
