💻 Laptop Price Prediction with Machine Learning
Predicting laptop prices using technical specifications and advanced regression techniques.




📘 Project Overview
This project focuses on building a machine learning model to predict laptop prices based on their technical specifications using a dataset sourced from Kaggle.

With over 1,200 entries and zero missing values, the dataset includes features such as:

- RAM

- CPU frequency

- Display type

- Operating system

 -Brand (60+ categories)

And more...

🧠 Goals
- Perform regression modeling to predict laptop prices

- Engineer and encode features appropriately

- Compare multiple regression models and tune hyperparameters

- Visualize model performance

⚒️ Key Challenges
- Encoding high-cardinality categorical features (e.g., 60+ laptop brands)

- Choosing the right encoding method: Label, One-Hot, Target, Ordinal

- Interpreting negative RMSE during cross-validation

- Balancing model complexity and interpretability

📊 Models & Techniques Used
- Gradient Boosting Regressor (GBR) — best performance after tuning

- Linear Regression (baseline)

- Random Forest Regressor

- GridSearchCV for hyperparameter tuning

- Pipelines with scikit-learn

- Data visualization with matplotlib and seaborn

📈 Performance
Metric	Value
- Initial RMSE	~183.12
- Tuned RMSE	~176.43

Fine-tuning the Gradient Boosting model significantly improved prediction accuracy.

📁 Project Structure
bash
📦 laptop-price-prediction/
├── data/                   # Raw dataset (not included in repo)
├── notebooks/              # Jupyter notebooks for EDA, modeling
├── src/                    # Modular scripts for preprocessing, training
├── models/                 # Saved models and tuning results
├── README.md               # Project overview
└── requirements.txt        # Python dependencies
🔍 Insights
- RAM and CPU frequency were strong predictors of price

- Display type and brand added nuance to price variation

- Feature engineering and encoding were crucial for performance

- Visualizing residuals helped uncover model limitations

🚀 How to Run
Clone the repo:

bash
git clone https://github.com/Doyinakinloye/laptop-price-prediction.git
cd laptop-price-prediction
Create and activate a virtual environment:

bash

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
Install dependencies:

bash

pip install -r requirements.txt
Run the notebook:

bash
Copy code
jupyter notebook notebooks/modeling.ipynb
📚 Dataset
Source: Kaggle Laptop Price Dataset

Note: Dataset not included due to licensing. Please download it manually.

🤝 Let's Connect!
Have questions about regression workflows, model tuning, or feature engineering?
Feel free to connect or reach out:

LinkedIn: www.linkedin.com/in/akinloye-oluwadoyinsolami-66b7a72b9

Email: doyinakinloye07@gmail.com

🏷️ Tags
#MachineLearning #Regression #FeatureEngineering #GradientBoosting #DataScience #Python #KaggleProject
