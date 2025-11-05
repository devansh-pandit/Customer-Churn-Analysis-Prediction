📊 Customer Churn Analysis Prediction
🔍 Project Overview
This project analyzes Telco customer data to predict customer churn. By identifying customers likely to leave, businesses can take proactive steps to improve retention and reduce revenue loss.

📁 Dataset
The dataset includes customer details such as service plans, usage behavior, and churn status. Key features:
- tenure: Number of months a customer has stayed with the company
- InternetService: Type of internet service (DSL, Fiber optic, None)
- PaymentMethod: Method of payment
- Churn: Target variable (Yes = churned, No = stayed)

⚙️ Features & Preprocessing
- Handled missing values and converted numerical features as needed
- Encoded categorical variables using Label Encoding
- Performed feature importance analysis to identify key churn drivers
- Scaled features using StandardScaler for improved model performance

🤖 Model
- Used Random Forest Classifier to predict customer churn
- Achieved 78% accuracy on the test set

📈 Insights
- Identified key factors influencing customer churn
- Provided actionable recommendations to improve customer retention

🧰 Tech Stack
Languages/Libraries: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Tools: Jupyter Notebook, Google Colab

🚀 How to Run
1. Clone the repository
git clone https://github.com/devansh-pandit/Customer-Churn-Analysis-Prediction.git


2. Install required packages
pip install -r requirements.txt


3. Run the notebook or script
Open churn_analysis.ipynb in Jupyter Notebook or Google Colab.
