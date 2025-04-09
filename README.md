🚗 Electric Vehicle Data Analysis & Price Category Prediction
A comprehensive data analysis project focused on Electric Vehicles (EVs) in Washington State, exploring trends, identifying outliers, performing statistical analysis, and building a machine learning model to predict vehicle price categories.

📊 Project Overview
This project involves:

Cleaning and preparing real-world EV registration data

Performing insightful Exploratory Data Analysis (EDA)

Engineering useful features (e.g., Vehicle Age, Range Category)

Detecting and handling outliers using the IQR method

Conducting statistical tests (T-Test)

Predicting price categories using Logistic Regression

🧰 Tools & Technologies
Python

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – Machine learning and evaluation

Jupyter Notebook – Development environment

Imbalanced-learn – Handling class imbalance

✅ Key Features
🚗 Identified EV adoption patterns across counties and cities

📈 Detected outliers in pricing and electric range

📊 Performed statistical T-Test to compare Tesla vs Non-Tesla vehicles

🤖 Trained a Logistic Regression model to predict price category

🎯 Achieved 88% model accuracy

📁 Project Structure
bash
Copy
Edit
├── EV_Analysis_Project.ipynb     # Main Jupyter notebook
├── cleaned_ev_data.csv           # Cleaned dataset
├── README.md                     # Project overview
└── /images                       # (Optional) For visualizations
📌 Results & Insights
Tesla vehicles have a significantly higher electric range on average (p-value = 0.0)

Most EVs are located in Seattle, Bellevue, and Redmond

Range and pricing show a strong correlation

The model accurately classifies vehicles into Premium, Mid-Range, or Luxury categories

💡 Future Improvements
Try advanced models like Random Forest or XGBoost

Build a dashboard using Streamlit

Include geographical visualizations with Plotly or Folium

👨‍💻 Author
Qaleel Sha Backer
B.Tech CSE (Specialization in Data Science and ML) | LPU
LinkedIn: https://www.linkedin.com/in/qaleel-sha-backer/ 

📌 License
This project is open-source and free to use under the MIT License.
