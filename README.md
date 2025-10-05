# 🚢 Titanic Survival Prediction – Logistic Regression (From Scratch)

This project implements a **Logistic Regression model from scratch (using only NumPy)** to predict passenger survival on the famous **Titanic dataset**.

---

## 📊 Project Overview

The goal of this project is to predict whether a passenger survived or not based on features like:
- Age  
- Gender  
- Passenger class  
- Number of siblings/spouses aboard  
- Number of parents/children aboard  
- Fare  

The project demonstrates **core concepts of Machine Learning**, including:
- Data preprocessing  
- Feature scaling  
- Gradient Descent optimization  
- Regularization  
- Model evaluation  

---

## 🧠 Concepts Used

- Logistic Regression  
- Sigmoid Activation Function  
- Cost Function with Regularization  
- Gradient Descent Optimization  
- Accuracy Evaluation  

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries Used:**  
  - NumPy  
  - Pandas  
  - Matplotlib (for visualization)  

---

## 📁 Project Structure



titanic-logistic-regression/
│
├── titanic_project.ipynb # Jupyter notebook containing full implementation
├── data/ # Folder containing Titanic dataset (if applicable)
│ └── train.csv
├── README.md # Project documentation (this file)
└── requirements.txt # Python dependencies (optional)


---

## 🚀 Steps Performed

1. **Data Loading & Exploration**
   - Read the Titanic dataset using Pandas  
   - Checked missing values and data distribution  

2. **Data Preprocessing**
   - Filled missing values (e.g., Age, Embarked)
   - Encoded categorical columns (`Sex`, `Embarked`)
   - Feature scaling using standardization  

3. **Model Implementation**
   - Implemented logistic regression manually using NumPy  
   - Defined cost and gradient functions with regularization  
   - Performed gradient descent optimization  

4. **Model Evaluation**
   - Calculated training accuracy  
   - Plotted cost vs. iterations  

---

## 📈 Results

| Metric | Value |
|--------:|------:|
| Training Accuracy | ~80–85% |
| Cost Reduction | From ~3.9 → ~1.5 after 10,000 iterations |

---

## 🧩 Key Learnings

- How logistic regression works **mathematically**  
- How **gradient descent** optimizes parameters  
- Importance of **feature scaling** and **regularization**  
- Building a full ML pipeline **without using sklearn**

---

## 💡 Future Improvements

- Add test data evaluation  
- Try using Scikit-Learn for comparison  
- Experiment with polynomial features  

---

## 👩‍💻 Author

**Vyshu Devasani**  
📧 [Your Email Here]  
🌐 [GitHub Profile](https://github.com/yourusername)

---

⭐ **If you found this project helpful, consider giving it a star on GitHub!**
