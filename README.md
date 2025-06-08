# Extrovert vs Introvert Personality Classifier

This project presents a clean machine learning pipeline to classify individuals as **Introverts** or **Extroverts** based on behavioral traits. The entire workflow is implemented in a single Jupyter notebook: `Data_Processing_Workflow.ipynb`.

---

## 📊 Dataset

- **Source:** [Kaggle – Extrovert vs. Introvert Behavior Data](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)
- **Size:** ~2,900 rows × 8 columns
- **Target Column:** `Personality` (Extrovert / Introvert)

---

## 🧠 Workflow Overview

The notebook includes:

- **Data Cleaning**
  - Handles missing values (drops or imputes based on threshold)
  - Encodes categorical values (`Yes`/`No` → Boolean)
  - Strips whitespace and removes duplicate entries
  - Encodes `Personality`: Introvert → 1, Extrovert → 0

- **Data Preparation**
  - Splits data into training and test sets

- **Model Training**
  - Uses Logistic Regression with class balancing
  - Evaluates with accuracy and classification report

- **Model Saving**
  - Trained model saved using `joblib` for future use

---

## ✅ Getting Started

### 1. Clone the Repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies
```
pip install -r requirements.txt
```

### 3. Run the notebook
```
jupyter notebook Data_Processing_Workflow.ipynb
```
