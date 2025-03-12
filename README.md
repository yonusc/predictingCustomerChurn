# About
This project is focused on predicting customer churn for a telecom company using various machine learning models. By analyzing customer data, the project identifies patterns and factors that contribute to customer churn. The models used include Logistic Regression, Decision Tree, Random Forest, k-Nearest Neighbors, and Support Vector Machines, implemented in a Python environment using libraries such as Pandas, Scikit-Learn, and Matplotlib.

## Getting Started
## Prerequisites
Ensure you have the following installed on your system to run this application:

- Python 3.x
- pip (Python package installer)

### Dependencies
This project depends on several Python libraries, including:

- pandas for data manipulation and analysis.
- matplotlib and seaborn for data visualization.
- plotly for interactive plots.
- sklearn for implementing machine learning models and metrics.

Install these dependencies using pip with the following command:

    python -m pip install pandas matplotlib seaborn plotly sklearn

#### Configuration
Data Files: Ensure that the dataset WA_Fn-UseC_-Telco-Customer-Churn.csv is placed in the project directory or adjust the path in the code accordingly.
Environment: No additional environment variables or configuration files are required.

##### Usage
To run the analysis:

- Clone the repository to your local machine.
    git clone <repository-url>

- Navigate to the directory containing the project files.

- Start the Jupyter Notebook or Python script that contains the analysis:
    jupyter notebook TelecomCustomerChurn-4.ipynb

    python script_name.py

###### Notebook/Script Structure
Data Loading and Cleaning: Load the telecom dataset and perform initial cleaning steps such as handling missing values and removing unnecessary columns.
Exploratory Data Analysis (EDA): Visualize different aspects of the data through histograms, pie charts, and bar plots to understand the distribution of various features and their relationship with churn.
Data Preprocessing: Scale numerical features and encode categorical features to prepare data for modeling.
Model Training and Evaluation: Train various machine learning models and evaluate their performance using metrics like accuracy, precision, recall, and F1-score.
Results Comparison: Compare the performance of the models to determine which model predicts customer churn most effectively.