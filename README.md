# Customer Churn Analysis Prediction

## Project Overview
This project analyzes Telco customer data to predict customer churn. By identifying customers likely to leave, businesses can take proactive steps to improve retention and reduce revenue loss.

## Dataset
The dataset contains customer details such as service plans, usage behavior, and churn status. Key features include:

- tenure: Number of months a customer has stayed with the company  
- InternetService: Type of internet service (DSL, Fiber optic, None)  
- PaymentMethod: Method of payment  
- Churn: Target variable (Yes = churned, No = stayed)  

## Features & Preprocessing
- Handled missing values and converted numerical features as needed  
- Encoded categorical variables using Label Encoding  
- Performed feature importance analysis to identify key factors influencing churn  
- Scaled features using StandardScaler for better model performance  

## Model
- Used a *Random Forest Classifier* to predict customer churn  
- Achieved *78% accuracy* on the test set  

## Insights
- Identified key factors driving customer churn  
- Provided actionable insights for improving customer retention  

## Tech Stack
- *Languages/Libraries:* Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- *Tools:* Jupyter Notebook, Google Colab  

## How to Run
1. Clone the repository:  
bash
git clone <repository_url>
`

2. Install required packages:

bash
pip install -r requirements.txt


3. Run the Jupyter Notebook or Python script
