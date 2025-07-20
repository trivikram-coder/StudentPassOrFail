# 🎓 Student Pass/Fail Prediction using Logistic Regression

This project uses a logistic regression model to predict whether a student will pass or fail based on their study hours and previous academic performance.

---

## 📊 Dataset

The dataset (`student_scores.csv`) contains the following columns:

- `study_hours`: Hours spent studying per day
- `previous_marks`: Previous exam scores (out of 100)
- `pass_or_fail`: Target class — 1 = Pass, 0 = Fail

### Sample data:

| study_hours | previous_marks | pass_or_fail |
|-------------|----------------|---------------|
| 1.0         | 35             | 0             |
| 3.5         | 50             | 1             |
| 7.0         | 70             | 1             |

---

## 🧠 ML Model

- **Algorithm:** Logistic Regression
- **Split:** 80% training / 20% testing
- **Libraries Used:** 
  - pandas
  - scikit-learn
  - matplotlib

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/StudentPassPredictor.git
   cd StudentPassPredictor
