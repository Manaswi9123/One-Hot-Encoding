# One-Hot-Encoding
# 🔢 Categorical Encoding: One-Hot Encoding (OHE)

Machine Learning models speak the language of numbers, not text. This repository demonstrates the essential preprocessing technique of **One-Hot Encoding** to transform categorical variables into binary vectors without implying any mathematical order.

---

## 🛠️ The Preprocessing Stack
* **Python**: Core logic.
* **Pandas**: Using `get_dummies` for quick, readable encoding.
* **Scikit-Learn**: Using `OneHotEncoder` for professional, pipeline-ready transformations.
* **Matplotlib/Seaborn**: For visualizing data before and after encoding.

---

## 💡 Key Concepts Implemented

### 1. The "Dummy Variable" Approach
* Created binary columns (0s and 1s) for each unique category in the dataset.
* **The Dummy Variable Trap:** Handled multicollinearity by dropping one of the encoded columns (`drop_first=True`), ensuring the model remains statistically sound.

### 2. Scikit-Learn OneHotEncoder
* Used the `OneHotEncoder` class to fit and transform the data.
* Demonstrated how to handle new data consistently using the same encoder object.

### 3. Comparison of Methods
* **Pandas `get_dummies`:** Great for quick Exploratory Data Analysis (EDA).
* **Sklearn `OneHotEncoder`:** Better for production Machine Learning pipelines where consistency between training and testing data is critical.

---

## 📉 Why One-Hot Encoding?
Unlike **Label Encoding** (which assigns 1, 2, 3...), **One-Hot Encoding** ensures the model doesn't mistakenly think that "Category 3" is "greater than" or "better than" "Category 1." This is crucial for non-ordinal data like City Names, Colors, or Device Types.



---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git](https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git)
