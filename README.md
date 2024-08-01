### Predicting Customer Churn for Telecom Growth

#### Project Overview
Customer churn is a critical issue for telecom companies, impacting revenue directly. This project tackles this problem by developing a predictive model to forecast customer attrition, aiding telecom operators in implementing effective retention strategies.

#### Key Features
- **Churn Prediction Model**: Forecasts customer churn to help devise proactive retention strategies.
- **Advanced Feature Engineering**: Utilizes innovative feature engineering and selection techniques.
- **Performance Metrics**: Achieved up to 93.3% AUC by integrating Social Network Analysis (SNA) features.
- **Algorithm Comparison**: Evaluated Decision Tree, Random Forest, Gradient Boosted Machine (GBM), and XGBoost, with XGBoost showing superior performance.

#### Dataset Information
- **customerID**: Customer ID
- **gender**: Whether the customer is a male or a female
- **SeniorCitizen**: Whether the customer is a senior citizen or not (1, 0)
- **Partner**: Whether the customer has a partner or not (Yes, No)
- **Dependents**: Whether the customer has dependents or not (Yes, No)
- **tenure**: Number of months the customer has stayed with the company
- **PhoneService**: Whether the customer has a phone service or not (Yes, No)
- **MultipleLines**: Whether the customer has multiple lines or not (Yes, No, No phone service)
- **InternetService**: Customer’s internet service provider (DSL, Fiber optic, No)
- **OnlineSecurity**: Whether the customer has online security or not (Yes, No, No internet service)
- **OnlineBackup**: Whether the customer has online backup or not (Yes, No, No internet service)
- **DeviceProtection**: Whether the customer has device protection or not (Yes, No, No internet service)
- **TechSupport**: Whether the customer has tech support or not (Yes, No, No internet service)
- **StreamingTV**: Whether the customer has streaming TV or not (Yes, No, No internet service)
- **StreamingMovies**: Whether the customer has streaming movies or not (Yes, No, No internet service)
- **Contract**: The contract term of the customer (Month-to-month, One year, Two year)
- **PaperlessBilling**: Whether the customer has paperless billing or not (Yes, No)
- **PaymentMethod**: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- **MonthlyCharges**: The amount charged to the customer monthly
- **TotalCharges**: The total amount charged to the customer
- **Churn**: Whether the customer churned or not (Yes, No)

#### Prerequisites
Before running the project, ensure you have the following installed:
- **Python 3.x**: Install from Python's official website.
- **Jupyter Notebook**: Install using pip:
  ```bash
  pip install notebook
  ```
- **Required Python Packages**: Install using pip from the `requirements.txt` file:
  ```bash
  pip install -r requirements.txt
  ```
  The `requirements.txt` file includes packages such as:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - matplotlib

#### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ajaneeshwar/Predicting-Customer-Churn-for-Telecom-Growth.git
   cd Predicting-Customer-Churn-for-Telecom-Growth
   ```
2. **Install Dependencies**: Make sure you have Python and Jupyter Notebook set up, then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. **Open and Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   Open the provided Jupyter notebook file in your browser and execute the cells to train and evaluate the churn prediction model.

#### License
This project is licensed under the MIT License - see the LICENSE file for details.

#### Acknowledgements
- **Machine Learning Libraries**: scikit-learn, XGBoost
- **Data Source**: Dataset provided by SyriaTel

#### Queries
For any questions or queries, please contact me via email: ajaneeshwar05@gmail.com or connect with me on [LinkedIn](http://www.linkedin.com/in/ajaneeshwar-s-378818250).
