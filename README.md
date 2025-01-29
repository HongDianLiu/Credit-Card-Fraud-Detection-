# Credit Card Fraud Detection

A parallel computing and machine learning project for detecting fraudulent transactions in digital banking using Dask, Joblib, and Multiprocessing.

## 📋 Overview

This project implements advanced fraud detection techniques using parallel computing frameworks to process large-scale banking transaction data. The implementation focuses on optimizing performance through various parallel processing methods while maintaining high detection accuracy.

### 🔑 Key Features

- **Efficient Data Processing:** Optimized handling of large-scale transaction datasets
- **Advanced Model Training:** Random Forest implementation with Optuna optimization
- **Multiple Parallelization Methods:**
  - Multiprocessing for fastest execution
  - Joblib for efficient processing with simple implementation
  - Dask for scalable, distributed computing
- **Performance Analysis:** Comprehensive comparison of different parallel processing approaches

## 📂 Project Structure

```
Credit Card Fraud Detection/
│
├── Final Report - Team 3.docx    # Detailed project documentation
├── Team3D.ipynb                  # Main implementation notebook
└── data/                         # Dataset directory
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Required libraries (install via pip):
  ```bash
  pip install dask joblib numpy pandas scikit-learn optuna
  ```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open `Team3D.ipynb` and run the cells sequentially

## 📊 Performance Insights

Our analysis revealed different performance characteristics for each parallel processing method:

- **Multiprocessing:** Best for CPU-intensive tasks with minimal inter-process communication
- **Joblib:** Good balance of ease-of-use and performance
- **Dask:** Optimal for distributed computing with very large datasets

## 🔍 Dataset

This project uses the Bank Account Fraud Dataset from NeurIPS 2022, which provides a comprehensive set of transaction data for fraud detection analysis.

## 📚 References

- [Bank Account Fraud Dataset (NeurIPS 2022)](https://neurips.cc/Conferences/2022)
- [Dask Documentation](https://docs.dask.org/)
- [Joblib Documentation](https://joblib.readthedocs.io/)
- [Python Multiprocessing](https://docs.python.org/3/library/multiprocessing.html)

## 👥 Contributors

- Team 3 Members (Add your team members' names/links here)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details
