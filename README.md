Updated README - Credit Card Fraud Detection

Project Overview

This project focuses on detecting fraudulent transactions using parallel computing and machine learning. We leverage Dask, Joblib, and Multiprocessing to improve processing efficiency.
	•	Dataset: Bank Account Fraud Dataset (NeurIPS 2022)

Setup & Installation
	1.	Install dependencies

pip install -r requirements.txt


	2.	Run Jupyter Notebook

jupyter notebook

Open Team3D.ipynb and execute all cells.

	3.	Run Python Script (if applicable)

python fraud_detection.py



Project Structure

📂 Credit Card Fraud Detection
│── 📄 Final Report - Team 3.docx  
│── 📄 Team3D.ipynb  
│── 📄 requirements.txt  
│── 📄 fraud_detection.py  
│── 📂 data (if applicable)  

Run Parallel Processing

1. Dask

dask-scheduler  
dask-worker localhost:8786  
python fraud_detection.py  

2. Joblib

from joblib import Parallel, delayed  
Parallel(n_jobs=-1)(delayed(my_function)(i) for i in range(100))

3. Multiprocessing

from multiprocessing import Pool  
pool = Pool(processes=4)  
result = pool.map(my_function, data_list)  

Key Features
	•	Data Processing: Uses Dask for handling large datasets.
	•	Model Training: Implements Random Forest + Optuna for hyperparameter tuning.
	•	Parallelization: Compares Dask, Joblib, and Multiprocessing for speedup.
	•	Performance Insights:
	•	Multiprocessing: Fastest processing.
	•	Joblib: Efficient but slightly slower.
	•	Dask: Best for large-scale datasets.

References
	•	Dask Docs
	•	Joblib Guide
	•	Python Multiprocessing

For questions, contact HongDian Liu & Team 3 🚀

Requirements.txt

Here’s the requirements.txt file for installation:

numpy  
pandas  
scikit-learn  
matplotlib  
seaborn  
optuna  
joblib  
dask  
jupyter  

Save this as requirements.txt in your project folder and install dependencies using:

pip install -r requirements.txt# Credit-Card-Fraud-Detection-
