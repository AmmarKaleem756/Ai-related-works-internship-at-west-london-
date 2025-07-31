# 📊 ML Classification: PhDs Produced by Pakistani Universities (2010–2014)

This project applies various machine learning classification models to predict whether a university in Pakistan is **Public** or **Private** based on the number of PhDs it produced from **2010 to 2014**.

---

## 📁 Dataset

- **Source**: HEC (Higher Education Commission), Pakistan
- **Features**: Number of PhDs produced per year from 2010 to 2014
- **Target**: `Sector` → Public (1) or Private (0)

### 🔸 Columns:
| Year Columns | Description         |
|--------------|---------------------|
| `2010`–`2014` | PhDs produced each year |
| `Sector`     | Target (Public/Private) |

---

## 🔄 Preprocessing

- ✅ Dropped unnecessary columns: `S#`, `Institute`
- ✅ Label encoded target: `Public` → 1, `Private` → 0
- ✅ Handled missing values (none found)
- ✅ Scaled numerical features using `StandardScaler`

---

## 🧠 Models Applied

| No. | Model                  |
|-----|------------------------|
| 1   | Logistic Regression    |
| 2   | Decision Tree          |
| 3   | Random Forest          |
| 4   | K-Nearest Neighbors    |
| 5   | Support Vector Machine |
| 6   | Naive Bayes            |
| 7   | XGBoost                |

Each model was evaluated using:

- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ F1 Score
- ✅ Confusion Matrix (visual)

---

## 📊 Performance Comparison

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.94     | 0.92      | 0.96   | 0.94     |
| Decision Tree       | 0.87     | 0.86      | 0.89   | 0.87     |
| Random Forest       | 0.96     | 0.94      | 0.98   | 0.96     |
| KNN                 | 0.85     | 0.83      | 0.88   | 0.85     |
| SVM                 | 0.92     | 0.91      | 0.93   | 0.92     |
| Naive Bayes         | 0.80     | 0.78      | 0.83   | 0.80     |
| **XGBoost**         | **0.97** | **0.95**  | **0.99** | **0.97** |

🎯 **Best Performing Model**: **XGBoost**

---

## 📈 Visuals

- Bar chart of all model scores (Accuracy, Precision, Recall, F1 Score)
- Confusion matrices for each model

<p align="center">
  <img src="https://img.shields.io/badge/ML%20Models-Compared-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Data-HEC-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/XGBoost-Top%20Performer-orange?style=flat-square"/>
</p>

---

## 🛠️ Tech Stack

- **Language**: Python 🐍
- **Libraries**:
  - `pandas`, `numpy`, `scikit-learn`
  - `xgboost`
  - `matplotlib`, `seaborn`

- **Platform**: Google Colab / Jupyter Notebook

---

## 📌 Future Improvements

- Include more features (e.g., funding, faculty size)
- Expand dataset to include more recent years
- Use model tuning or deep learning for optimization

---

## 🤝 Author

- 👤 **Ammar Kaleem**
- 📬 Email: *ammarkaleemofficial@gmail.com*
- 💼 BSAI Student | AI Enthusiast

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
