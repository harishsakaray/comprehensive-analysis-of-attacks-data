# Strengthening Business Security: Predictive Analytics of Cybersecurity Trends Using CISSM Data

## Code Description

This project contains a code file named BFOR515_Group6_Project_Code.ipynb file(also available in .py format) that performs the following tasks:

1. Data Loading and Cleaning: Loads an Excel file containing cyber threat data and cleans it by handling missing values and converting data types.
2. Exploratory Data Analysis: Performs descriptive analysis to understand the patterns in data, including outlier detection and distribution analysis.
3. Feature Engineering: Creates new features to improve model accuracy, such as temporal features and interaction terms.
4. Data Encoding: Encodes categorical features using frequency encoding, label encoding, and one-hot encoding.
5. Model Training: Trains an XGBoost classifier to predict event types based on the engineered features.
6. Model Evaluation: Evaluates the model's accuracy and performance using metrics like accuracy score and classification report.
7. Future Prediction: Uses the trained model to predict future cyber threat trends for the next 5 years.
8. Visualization: Creates charts and graphs to visualize the results, including a heatmap showing predicted event types over time.


## Data Description

The project utilizes a dataset named attacks_data.xlsx` containing information about cyber threat events. 

Dataset Columns:

- event_date: Date of the cyber threat event.
- year: Year of the event.
- month: Month of the event.
- actor: Entity responsible for the event.
- actor_type: Type of entity (e.g., Hacktivist, State-Sponsored).
- motive: Reason for the attack.
- industry: Targeted industry.
- industry_code: Industry code.
- country: Country where the event occurred.
- actor_country: Country of the entity responsible.
- event_type: Type of cyber threat event (e.g., Disruptive, Exploitive).
- description: Description of the event.
- source_url: Source of information about the event.



## Instructions to Run the Code

- Ensure you have Google Colab or a Jupyter Notebook environment.
- Install the required libraries:panda,numpy,scipy,scikit-learn,matplotlib,seaborn,xgboost