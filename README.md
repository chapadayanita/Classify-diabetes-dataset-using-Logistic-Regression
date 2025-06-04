# 🩺 Diabetes Prediction using Logistic Regression

This project demonstrates how to use **Logistic Regression** to classify whether a patient has diabetes based on medical diagnostic measurements.

## 📁 Dataset

The dataset used is `diabeties.csv` (based on the Pima Indians Diabetes Database), which contains the following columns:

| Feature                    | Description                                      |
|---------------------------|--------------------------------------------------|
| `Pregnancies`             | Number of times pregnant                         |
| `Glucose`                 | Plasma glucose concentration                     |
| `BloodPressure`           | Diastolic blood pressure (mm Hg)                 |
| `SkinThickness`           | Triceps skin fold thickness (mm)                |
| `Insulin`                 | 2-Hour serum insulin (mu U/ml)                   |
| `BMI`                     | Body mass index (weight in kg/(height in m)^2)  |
| `DiabetesPedigreeFunction`| Diabetes pedigree function                       |
| `Age`                     | Age in years                                     |
| `Outcome`                 | Class variable (0 = Non-diabetic, 1 = Diabetic) |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib

## 🔍 Workflow

1. **Data Loading** from CSV file
2. **Train-Test Split** (80% training, 20% testing)
3. **Model Training** using Logistic Regression
4. **Prediction** on test data
5. **Evaluation** using:
   - Accuracy
   - Classification Report
   - Confusion Matrix
6. **Sigmoid Function Plotting** for conceptual understanding

## 📊 Evaluation Output

- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-Score)
- **Confusion Matrix**
- **Sigmoid Curve Plot**: Visualization of the logistic (sigmoid) function
