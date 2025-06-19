# Practical-Lab2-9013742



## Markdown Descriptions
# Practical Lab 2: Multivariate Linear Regression, Non-Parametric Models and Cross-Validation  
## Student Name: Jahnavi Pakanati  
## Student  ID: 9013742
### Course code: CSCN8010

## Part-1

### 1. Getting  the Data

### 2. Problem **Objective:  Predict "disease progression one year after baseline" (target variable `y`) based on patient features (X).

### 3. Defining the EDA - Exploratory Data Analysis

####  Plotting the Scatter Plot

#### Histogram:

#### Heat Map:

## Insights based on the  EDA plots:

1. There is a high correlation between BMI and disease progression:

The target vs. BMI scatter plot shows a strong positive trend, i.e., higher BMI values are associated with higher disease progression.

The correlation matrix confirms the same with a strong correlation coefficient of 0.59 between BMI and target variable.

Step 1: Set Up Python Environment (Optional but Recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Step 2: Install Dependencies

pip install -r requirements.txt

