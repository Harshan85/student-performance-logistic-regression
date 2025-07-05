# student-performance-logistic-regression
A simple logistic regression model to predict student performance.
# Objective
Predict whether a student will pass or fail based on:
- Hours Studied
- Attendance %

## Tools Used
- Python
- Google Colab / Jupyter Notebook
- Libraries: pandas, sklearn, matplotlib

## Steps
1. Manually created dataset with study hours and attendance.
2. Trained Logistic Regression model.
3. Evaluated accuracy.
4. Made custom predictions.

## How to Run
- Open `Student_Performance.ipynb` in Google Colab or Jupyter.
- Run all cells to train and test the model.

## Sample Prediction
```python
model.predict([[3, 80]])  # Output: 1 (Pass)

