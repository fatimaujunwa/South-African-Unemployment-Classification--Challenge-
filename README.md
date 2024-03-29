# South African Youth Employment Prediction Challenge
This project involves predicting the employment status of youth in the South African labour market one year after the baseline survey. The data spans four rounds of surveys conducted at 6-month intervals, containing numerical, categorical, and free-form text responses. Demographic information such as age, school level, and results is also provided.

## Challenge Overview
Data Source: Four rounds of a survey of youth in the South African labour market, conducted at 6-month intervals.
Features: Numerical, categorical, and free-form text responses, along with additional demographic information.
Objective: Predict whether a person is employed at the follow-up survey based on their baseline data.
Training Set: One row per individual, including baseline information and the target outcome (employed or not) one year later.
Test Set: Baseline data without the target outcome.
Model Details
Algorithm Used: Light Gradient Boosting Machine (LGBM)
Validation Set Accuracy: 97.3%
Project Structure
data/: Contains the dataset used for training and testing.
notebooks/: Jupyter notebooks used for data exploration, feature engineering, and model training.
src/: Source code for the LGBM algorithm implementation.
models/: Saved models and model-related files.
results/: Evaluation metrics, visualizations, and insights derived from the model.
## How to Use
Clone the Repository:

Clone this repository to your local machine using the following command:
bash
Copy code
git clone https://github.com/yourusername/south-africa-youth-employment.git
Explore the Code:

Dive into the notebooks/ and src/ directories to understand the data analysis, feature engineering, and model implementation.
Reproduce Results:

Follow the steps in the Jupyter notebooks to reproduce the model training and evaluation results.

## Acknowledgments
Data provided by Predictive Insights.
The algorithm used, LGBM, demonstrated an accuracy of 97.3% on the validation set.
