# PRODIGY_DS_03 : BANK_MARKETING
### Predicting Customer Subscription to Term Deposits using a Decision Tree Classifier 
# Table of Contents  
- [Description](#description)  
- [Overview](#overview)  
- [Data Source](#data-source)  
- [Installation](#installation)  
- [Usage](#usage)  
    - [Data Preprocessing and Analysis](#data-preprocessing-and-analysis)  
    - [Model Building and Evaluation](#model-building-and-evaluation)  
- [Recommendations](#recommendations)  
- [Contributors](#contributors)  
- [Contributing](#contributing)  
- [License](#license)  

___  

## Description  
This project aims to build a **Decision Tree Classifier** to predict whether a bank customer will subscribe to a term deposit. By analyzing features such as demographic data, contact history, and marketing campaign engagement, the model helps the bank target promising customers, improving marketing campaign effectiveness.  

___  

## Overview  
The project involves:  
1. Analyzing customer data to identify key predictors of subscription behavior.  
2. Building a baseline model for performance comparison.  
3. Developing a Decision Tree Classifier and evaluating its performance.  
4. Optimizing the model with hyperparameter tuning for better results.  
5. Generating actionable recommendations for enhancing the bank's marketing strategies.  

Key Python libraries used include `pandas`, `numpy`, `matplotlib`, `seaborn`, and `sklearn` for data manipulation, visualization, and modeling.  

___  

## Data Source  
The dataset used in this project is available on Kaggle: [Classification of Bank Deposit Using Decision Tree](https://www.kaggle.com/code/mehakiftikhar/classification-of-bank-deposit-using-decision-tree).  

___  

## Installation  

To set up the project, follow these steps:  

1. Clone the repository to your local machine:  
    ```bash  
    git clone https://github.com/ibtj21/PRODIGY_DS_03.git  
    ```  

2. Navigate to the project directory:  
    ```bash  
    cd PRODIGY_DS_03  
    ```  

3. Install the required dependencies:  
    ```bash  
    pip install -r requirements.txt  
    ```  

Dependencies include:  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

___  

## Usage  

### Data Preprocessing and Analysis  
1. **Data Cleaning**:  
   - Remove duplicate rows to ensure data quality.  
   - Handle missing values appropriately.  

2. **Exploratory Data Analysis**:  
   - Analyze key features and their distribution.  
   - Generate visualizations such as pie charts to understand the target variable (`deposit`).  

### Model Building and Evaluation  
1. **Baseline Model**:  
   - Establish a baseline by predicting the most frequent class.  
   - Use baseline accuracy as a benchmark.  

2. **Decision Tree Classifier**:  
   - Train a Decision Tree Classifier on the dataset.  
   - Tune hyperparameters (e.g., max depth, min samples split) for optimal performance.  

3. **Model Evaluation**:  
   - Assess the model using metrics such as accuracy, precision, recall, and F1-score.  
   - Visualize feature importance and tree structure for interpretability.  

Find the complete implementation [here](https://github.com/ibtj21/PRODIGY_DS_03/blob/main/Bank_Marketing.ipynb).  

___  

## Recommendations  

1. **Focus on High-Duration Calls**:  
   - Customers with longer call durations are more likely to subscribe, making duration a critical predictor.  

2. **Optimize Contact Methods**:  
   - Research and enhance the most effective contact methods to improve engagement.  

3. **Engage Customers Regularly**:  
   - Actively monitor and update the last contact date to ensure timely follow-ups, as recency strongly influences subscription likelihood.  

___  

## Contributors  
- Hanna Hailemarima Gashaw  

___  

## Contributing  
Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch (e.g., `feature/your-feature`).  
3. Commit your changes.  
4. Submit a pull request.  

Ensure your contributions align with the project's coding standards.  

___  

## License  
This project is licensed under the MIT License. See the [LICENSE](https://github.com/ibtj21/PRODIGY_DS_03/blob/main/LICENSE) file for details.  
  
