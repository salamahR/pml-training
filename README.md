# pml-training
# Practical Machine Learning - Prediction Assignment

This project is part of the Practical Machine Learning course on Coursera. It involves using accelerometer data to predict how participants performed barbell lifts.

## 🚀 Goal

To predict the manner in which a person performed the exercise (the `classe` variable) using sensor data from accelerometers on the belt, forearm, arm, and dumbbell.

## 📂 Files

- `pml-training.csv`: Training dataset.
- `pml-testing.csv`: Final test dataset for prediction (optional).
- `pml_project.Rmd`: R Markdown file with code and explanation.
- `pml_project.html`: Rendered HTML report from R Markdown.
- `final_predictions.txt`: File containing final 20 predictions (if generated).
- `README.md`: This file.

## 🔍 Methodology

- Cleaned the training data by removing columns with missing values and irrelevant metadata.
- Partitioned data into training and validation sets (70/30).
- Trained a Random Forest model using 5-fold cross-validation.
- Evaluated accuracy using a confusion matrix.
- (Optional) Predicted 20 test cases using the provided `pml-testing.csv`.

## 📦 Packages Used

- `caret`
- `randomForest`
- `dplyr`
- `e1071`

## 📈 Accuracy

Achieved high out-of-sample prediction accuracy (> 99%) using Random Forest.

## 📄 Output

To see the full analysis and results, view the `pml_project.html` file in a web browser.

## 🧪 Reproducibility

To reproduce this analysis, run the code in `pml_project.Rmd` using RStudio. All preprocessing steps are included.

## 🧑‍🏫 Course Instructions

Please refer to the [Course Project Prediction Quiz](https://www.coursera.org/learn/practical-machine-learning/) for submitting your 20 predictions from `pml-testing.csv`.
