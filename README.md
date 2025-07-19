# 🧠 Support Vector Classifier (SVC) Implementation

This project demonstrates the implementation and evaluation of a **Support Vector Classifier** using the `scikit-learn` library. It includes data generation, model training with different kernels
(Linear, RBF, Polynomial, Sigmoid), and hyperparameter tuning using GridSearchCV.

---

## 📊 Features

- Generates synthetic classification data
- Trains SVM with multiple kernels:
  - Linear
  - RBF (Radial Basis Function)
  - Polynomial
  - Sigmoid
- Compares classification metrics (Precision, Recall, F1-Score)
- Performs hyperparameter tuning with GridSearchCV
- Visualizes classification results

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Installation
1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/SVC-Implementation.git
   cd SVC-Implementation
   
2. **Install dependencies (optional)**

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn

3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook svc_implementation.ipynb


4. **Open ipynb file and run the cells.**


## 🔍 Kernel Performance Comparison

| Kernel     | Accuracy | Notes                       |
| ---------- | -------- | --------------------------- |
| Linear     | 96%      | Good baseline performance   |
| RBF        | 93%      | Improved after tuning       |
| Polynomial | 88%      | Lower accuracy              |
| Sigmoid    | 89%      | Acceptable but not optimal  |
| GridSearch | 93%      | Best tuned parameters found |


## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and open pull requests with improvements.

## 📄 License
This project is open-source and available under the MIT License.

## 👤 Author
Mai3Prabhu








