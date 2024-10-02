# supervised ML

# Student Scores Prediction using Simple Linear Regression

## Project Overview

This project aims to predict the scores of students based on the number of hours they studied. A simple linear regression model is used to build the prediction, where the independent variable is the number of study hours, and the dependent variable is the score achieved.

## Dataset

The dataset consists of two columns:

1. **Hours**: Number of hours a student studied.
2. **Scores**: Scores achieved by the student.

Sample data:
| Hours | Scores |
|-------|--------|
| 2.5   | 21     |
| 5.1   | 47     |
| 3.2   | 27     |
| 8.5   | 75     |
| 3.5   | 30     |
| 1.5   | 20     |

The dataset is loaded from a CSV file.

## Project Workflow

1. **Data Preprocessing**:
   - Load and visualize the dataset.
   - Plot the relationship between hours studied and scores to understand the data distribution.

2. **Model Training**:
   - The dataset is split into training and testing sets in an 80:20 ratio.
   - A linear regression model is trained on the training data.

3. **Model Evaluation**:
   - The model's performance is evaluated using the **Mean Absolute Error (MAE)**.
   - The regression line is plotted to visualize the model's predictions.
   
4. **Prediction**:
   - Predict scores for test data and compare them with actual scores.
   - Predict the score for a student who studied for 9.25 hours.

## Key Findings

- **Training Set MAE**: The Mean Absolute Error (MAE) on the training set was approximately `5.19`.
- **Test Set MAE**: The Mean Absolute Error (MAE) on the test set was approximately `4.18`, indicating good model performance.
- **Prediction for 9.25 hours of study**: The model predicts that a student who studies for 9.25 hours would score approximately `93.69`.

## Technologies Used

- **Python**: The programming language used to build the model.
- **Libraries**: 
  - `pandas` for data handling and manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` for data visualization.
  - `scikit-learn` for machine learning algorithms.

## How to Run the Project

1. Install the required dependencies by running:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

2. Open the Jupyter notebook `my_assignment1.ipynb` and run the cells step-by-step to see the workflow.

## Results Visualization

![Hours vs Scores](https://link_to_plot_image)

The above graph shows the relationship between the number of hours studied and the scores obtained by students.

---

Feel free to modify the content or add more details as necessary! Let me know if you'd like to make any adjustments.

