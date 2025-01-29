Credit Card Fraud Detection

Project Overview

This project focuses on detecting fraudulent transactions in digital banking using parallel computing and machine learning. By leveraging Dask, Joblib, and Multiprocessing, we enhance processing efficiency and improve fraud detection accuracy.
	•	Dataset: Bank Account Fraud Dataset (NeurIPS 2022)

Project Files

📂 Credit Card Fraud Detection
│── 📄 Final Report - Team 3.docx       # Detailed project report  
│── 📄 Team3D.ipynb                     # Jupyter Notebook with implementation  
│── 📂 data/                            # Dataset folder (if applicable)  

How to Use

Run Jupyter Notebook
	1.	Open a terminal and navigate to the project folder.
	2.	Start Jupyter Notebook:

jupyter notebook


	3.	Open Team3D.ipynb and run the cells sequentially.

Key Features
	•	Data Processing: Efficient handling of large datasets.
	•	Model Training: Implements Random Forest + Optuna for optimization.
	•	Parallelization: Compares Dask, Joblib, and Multiprocessing for performance.
	•	Performance Insights:
	•	Multiprocessing: Fastest execution.
	•	Joblib: Efficient but slightly slower.
	•	Dask: Ideal for large-scale datasets.

References
	•	Bank Account Fraud Dataset (NeurIPS 2022)
	•	Dask Documentation
	•	Joblib Guide
	•	Python Multiprocessing
