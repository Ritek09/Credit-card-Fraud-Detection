# Credit-card-Fraud-Detection

#Introduction
In today’s digital economy, credit card transactions occur every second worldwide, making fraud detection a crucial component of financial security. Traditional rule-based systems struggle to adapt to evolving fraud patterns, resulting in missed detections and false alerts.
This project presents a Credit Card Fraud Detection System that leverages Machine Learning to identify fraudulent transactions in real-time. The system uses a trained Random Forest Classifier and provides an interactive web-based dashboard for visual analytics and live predictions. It integrates model training, preprocessing, visualization, and deployment through Flask, ensuring scalability and usability for financial institutions and researchers.

#Objectives
• Develop a machine learning model capable of detecting fraudulent transactions.
• Handle imbalanced data using appropriate sampling and stratification techniques.
• Create a web dashboard for real-time fraud analytics and monitoring.
• Enable single transaction predictions with probability scoring.
• Implement secure dataset uploads and dynamic data visualization.
Scope of the Project
• Financial institutions seeking automated fraud monitoring solutions.
• Educational projects demonstrating end-to-end ML pipelines.
• Research on imbalanced dataset handling and fraud detection strategies.
• Extensible platform for integrating deep learning or streaming data in future upgrades.

#System Architecture
• Data Processing Layer (Pandas, NumPy, Scikit-learn):
Handles dataset loading, cleaning, feature scaling, and splitting for model training and testing.
• Machine Learning Layer (Random Forest Classifier):
Performs fraud classification with optimized accuracy and balanced prediction.
• Backend Layer (Flask):
Manages web routing, API endpoints, and integration between ML logic and visualization.
• Frontend Layer (HTML, CSS, JavaScript):
Presents an interactive dashboard for users to monitor fraud trends, visualize analytics, and test single transactions.

#Modules of the Project
• Model Training and Evaluation – Reads dataset, preprocesses features, and trains the Random Forest Classifier.
• Dashboard Analytics – Displays fraud statistics such as total transactions, fraud rate, and transaction amount analysis.
• Single Transaction Prediction – Allows users to input transaction features and receive real-time fraud probability.
• Dataset Upload & Validation – Accepts new CSV datasets, validates column structure, and updates live dashboard.
• Visualization Module – Shows fraud patterns by hour, amount distribution, and fraud-to-legit ratios through charts.

#Technologies & Tools Used
• Python (Pandas, NumPy, Scikit-learn, Joblib) – Core machine learning and preprocessing.
• Flask – Backend framework for serving APIs and UI.
• HTML, CSS, JavaScript – Frontend design and visualization.
• Matplotlib / Chart.js – For interactive data charts and fraud patterns visualization.
• Jupyter Notebook – Model training and result evaluation.
• MySQL (optional) – For storing transactional data.
• VS Code / PyCharm – Development environment.

#Expected Outcome
• A fully functional ML-based fraud detection web application.
• Accurate classification of legitimate and fraudulent transactions.
• Real-time fraud analytics and dynamic data visualization.
• Improved understanding of model deployment and data imbalance handling.
• Insight into how fraud patterns vary across time and amount ranges.

#Results and Analysis
• Algorithm Used: Random Forest Classifier
• Test Accuracy: ~99% (depending on dataset and parameters)
• Fraud Detection Rate: High precision on minority class
• False Positive Rate: Maintained within acceptable limits

#Challenges and Solutions
• Class Imbalance: Addressed using stratified sampling and ensemble learning.
• Data Privacy: Managed by using PCA-transformed anonymized data.
• Real-time Processing: Optimized feature preprocessing for quick API responses.

#Learning Outcomes
• Gained hands-on experience with real-world, highly imbalanced financial datasets.
• Learned to design interactive dashboards with Flask.
• Understood model deployment and live monitoring workflows.
• Improved skills in scaling features and optimizing ensemble classifiers.
• Gained insight into visual analytics and fraud behavior interpretation.

#Conclusion
The Credit Card Fraud Detection System successfully demonstrates the integration of machine learning, data visualization, and web deployment for real-time financial security. It identifies fraudulent patterns efficiently using a trained Random Forest model while providing an intuitive user interface for monitoring and analysis.
Future enhancements can include deep learning models, streaming data integration, and alert systems to strengthen real-time fraud prevention capabilities.

