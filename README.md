Customer Support Ticket Dataset
**Introduction**
This dataset contains customer support ticket data, which includes information about customer interactions with the support team for various product-related issues. 
It tracks the details of the ticket such as the type of issue, the product involved, the communication channel used, the resolution status, and the customer’s satisfaction rating.
This dataset can be useful for various analyses and business intelligence tasks such as:
Customer Satisfaction Analysis:
Understanding how quickly and effectively support tickets are resolved and how this correlates with customer satisfaction ratings.
Support Team Performance:
Analyzing the response time and resolution time to gauge the performance of customer support teams.
Product Issues and Trends:
Identifying common technical issues or product defects based on ticket descriptions and subjects.
Customer Demographics:
Analyzing if there are any trends in ticket submissions based on age, gender, or other demographic data.
The dataset includes the following columns:
- **Ticket ID**: Unique identifier for each customer support ticket
- **Customer Name**: Name of the customer who raised the support ticket
- **Product Purchased**: The product related to the ticket
- **Ticket Type**: Type of the issue (e.g., Technical issue, Billing inquiry)
- **Ticket Status**: Status of the ticket (e.g., Pending, Closed)
- **Resolution**: Resolution description (if available)
- **Ticket Priority**: Priority level of the ticket (e.g., Critical, Low)
- **First Response Time**: Time when the customer first received a response
- **Time to Resolution**: Time taken to resolve the issue
- **Customer Satisfaction Rating**: Rating given by the customer after the issue was resolved
### Data Preprocessing
- The `data_preprocessing.ipynb` notebook covers the steps to clean and preprocess the dataset, including handling missing values, encoding categorical variables, and feature engineering.

### Model Training
- The `model_training.py` script shows how to train machine learning models like Logistic Regression, Decision Trees, and Random Forest using the dataset. The models are evaluated using cross-validation, and hyperparameter tuning is performed to improve their performance.

### Example Analysis
- The `exploratory_analysis.ipynb` notebook contains exploratory data analysis (EDA), where we analyze trends, correlations, and visualize the data.

## File Descriptions
- `data/tickets_data.csv`: Raw dataset containing customer support tickets.
- `notebooks/data_preprocessing.ipynb`: Jupyter notebook for preprocessing and cleaning data.
- `notebooks/exploratory_analysis.ipynb`: Jupyter notebook for EDA and generating insights from the data.
- `src/model_training.py`: Python script for training and evaluating machine learning models.
- `src/feature_engineering.py`: Python script for creating new features or selecting important ones.
- `requirements.txt`: A list of dependencies required to run the project.

## Dependencies

This project uses the following Python packages:
- `pandas` for data manipulation
- `numpy` for numerical computations
- `scikit-learn` for machine learning
- `matplotlib` and `seaborn` for data visualization


