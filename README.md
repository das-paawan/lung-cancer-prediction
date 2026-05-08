# lung-cancer-prediction
Lung Cancer Prediction using ML
🫁 Lung Cancer Prediction using Machine Learning
A machine learning project focused on predicting the likelihood of lung cancer using patient health and lifestyle data. This project compares multiple ML algorithms and evaluates their performance to identify the most effective model for classification.

📌 Project Overview
Early detection of lung cancer can significantly improve treatment outcomes and survival rates. This project applies data preprocessing, feature engineering, balancing techniques, and multiple machine learning algorithms to build a predictive model capable of classifying whether a patient is at risk of lung cancer.

The notebook walks through:
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Handling imbalanced datasets using SMOTE
Training and evaluating multiple ML models
Comparing model performances
Generating predictions and evaluation metrics

🧠 Machine Learning Models Used
The following algorithms were implemented and evaluated:
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree Classifier
Support Vector Machine (SVM)
Naive Bayes
Random Forest Classifier

⚙️ Technologies & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-learn (SMOTE)
Jupyter Notebook

📂 Dataset
The dataset used for this project was sourced from Kaggle and contains patient-related attributes such as:
Age
Smoking habits
Anxiety levels
Peer pressure
Chronic diseases
Fatigue
Alcohol consumption
Chest pain
Breathing issues
Other health indicators

Target Variable:
LUNG_CANCER

🔄 Project Workflow
1. Data Preprocessing
Handling missing values
Encoding categorical variables
Feature selection
Splitting training and testing datasets

3. Exploratory Data Analysis
Correlation analysis
Distribution plots
Heatmaps and visualizations
Identifying class imbalance

5. Handling Imbalanced Data
SMOTE (Synthetic Minority Oversampling Technique) was applied to improve model performance and reduce bias caused by class imbalance.

7. Model Training & Evaluation
Each model was trained and evaluated using metrics such as:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix

📊 Results
The project compares multiple machine learning models to determine the best-performing classifier for lung cancer prediction.
Random Forest and ensemble-based approaches showed strong predictive performance during evaluation.

🚀 How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/lung-cancer-prediction.git

2. Navigate into the Project Folder
cd lung-cancer-prediction

3. Install Dependencies
pip install -r requirements.txt

4. Launch Jupyter Notebook
jupyter notebook

Open:
Lung Cancer Prediction.ipynb

📁 Project Structure
├── Lung Cancer Prediction.ipynb
├── README.md
├── requirements.txt
└── dataset/

🎯 Future Improvements
Deploy the model using Flask or FastAPI
Build an interactive web application
Improve performance using ensemble learning
Perform hyperparameter tuning
Integrate deep learning approaches
🤝 Contributing
Contributions, suggestions, and improvements are welcome.
Feel free to fork the repository and submit a pull request.
📜 License
This project is intended for educational and research purposes.
👨‍💻 Author
Developed by a Computer Science Engineering student passionate about AI, Machine Learning, and healthcare-focused predictive systems.
