This project aims to build a machine learning model to predict loan approval risks using a dataset from Kaggle.

## Dataset

The dataset contains the following key features:
- Id: Unique identifier for each loan applicant.
- Income: The income level of the applicant.
- Age: Age of the applicant.
- Experience: Years of professional experience.
- Married/Single: Marital status of the applicant.
- House_Ownership: Indicates whether the applicant owns or rents a house.
- Car_Ownership: Indicates whether the applicant owns a car.
- Profession: Occupation or profession of the applicant.
- CITY: City of residence of the applicant.
- STATE: State of residence of the applicant.
- CURRENT_JOB_YRS: Duration of employment in the current job.
- CURRENT_HOUSE_YRS: Duration of residence in the current house.
- Risk_Flag: Binary indicator of loan risk, where 1 represents a flagged risky applicant and 0 represents a non-risky applicant.

## Steps

1. **Data Exploration and Preprocessing**: Load the data, check for missing values and duplicates, encode categorical variables, and scale numerical features.
2. **Model Training**: Train a Random Forest classifier.
3. **Model Evaluation**: Evaluate the model using accuracy, precision, recall, and F1-score.
4. **Visualizations**: Include a correlation matrix heatmap, feature importances, and a confusion matrix.

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-approval-prediction.git
   cd loan-approval-prediction
