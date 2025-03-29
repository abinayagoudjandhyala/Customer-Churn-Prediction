# Customer Churn Prediction & Analysis

## Project Overview
This project predicts customer churn using a machine learning model and visualizes the results with an interactive Power BI dashboard. It uses classification algorithms to identify customers likely to churn based on service usage, demographics, and payment behavior.

---

## Project Structure
```
├── CustomerChurnPrediction.ipynb  # Jupyter Notebook for model training & prediction
├── customer_churn_model.pkl       # Trained machine learning model
├── churn_predictions.csv          # Prediction results for Power BI
├── WA_Fn-UseC_-Telco-Customer-Churn.csv # Original dataset
├── CustomerChurn.pbix    # Power BI dashboard file
└── README.md                      # Project documentation
```

---

## Dataset Description
The dataset contains customer data from a telecom company, including demographics, account information, and services used. The target variable is `Churn`, indicating whether the customer left the company.

**Dataset Link:** [Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

### Dataset Features
- `customerID`: Unique customer identifier
- `gender`: Gender of the customer
- `SeniorCitizen`: Whether the customer is a senior citizen (1, 0)
- `Partner`, `Dependents`: Family status
- `tenure`: Number of months as a customer
- `PhoneService`, `InternetService`, `Contract`, etc.
- `Churn`: Target variable (Yes/No)

---

## Machine Learning Model
1. Data Preprocessing: Handled missing values, encoded categorical data, and scaled numerical features.
2. Model Training: Built and trained a machine learning model using algorithms like RandomForest.
3. Prediction: Generated churn probabilities and labels for each customer.

---

## Power BI Dashboard
### Dashboard Title: Customer Churn Analysis Dashboard
#### Visualizations:
- **Overall Churn Rate** (Gauge)
- **Churn Prediction Distribution** (Histogram)
- **Customer Demographics Analysis** (Pie/Donut Chart)
- **Service Usage Impact** (Stacked Bar Chart)
- **Churn Probability vs. Tenure** (Scatter Plot)


---

## How to Run the Project
1. Clone the repository from GitHub:
```bash
git clone https://github.com/abinayagoudjandhyala/customer-churn-analysis.git
```
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook to generate predictions:
```bash
jupyter notebook CustomerChurnPrediction.ipynb
```
4. Import the CSV file into Power BI and create the dashboard using the above visualizations.

---

## Future Enhancements
- Optimize the model for better accuracy.
- Add more advanced visuals and insights in Power BI.
- Deploy the model using Flask or FastAPI.

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.


