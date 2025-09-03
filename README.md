# 🎯 Rock vs Mine Classification

This project predicts whether a sonar signal corresponds to a **Rock (R)** or a **Mine (M)** using **Logistic Regression**.

---

## 📌 Dataset
- **Source**: [Kaggle - Mines vs Rocks Dataset](https://www.kaggle.com/datasets/mattcarter865/mines-vs-rocks)  
- The dataset contains **208 samples** with **60 numerical features** and a label column (`R` = Rock, `M` = Mine).

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📊 Model Training
- Train-test split: **90% train / 10% test**  
- Algorithm: **Logistic Regression**  
- Accuracy achieved: **~85-90%** (varies slightly each run)

---

## 📈 Visualizations
Some graphs generated using Matplotlib:

- Count of Rock vs Mine signals  
- Feature distributions  
- Mean feature comparison (Rock vs Mine)  
- Confusion Matrix of predictions  

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/devendrakushwah80/rock-vs-mine-classification.git
   cd rock-vs-mine-classification
Install dependencies:

pip install -r requirements.txt
Open the Jupyter Notebook:

jupyter notebook sonar_classification.ipynb
🔮 Example Prediction
input_data = (
    0.0209, 0.0371, 0.0428, 0.0209, 0.0954, 0.0986, 0.1539, 0.1601,
    0.3109, 0.2111, 0.1609, 0.1582, 0.2238, 0.0645, 0.0660, 0.2273,
    0.3100, 0.2999, 0.5078, 0.4797, 0.5783, 0.5071, 0.4328, 0.5550,
    0.6711, 0.6415, 0.7104, 0.8080, 0.6791, 0.3857, 0.1309, 0.2604,
    0.5129, 0.7547, 0.8537, 0.8510, 0.6692, 0.6097, 0.4940, 0.2744,
    0.0510, 0.2834, 0.2826, 0.4256, 0.2641, 0.1386, 0.1051, 0.1343,
    0.0383, 0.0324, 0.0478, 0.0370, 0.0061, 0.0125, 0.0084, 0.0089,
    0.0048, 0.0094, 0.0151, 0.0072
)
prediction = model.predict([input_data])


👉 Output:

ALERT !! THIS IS MINE !!
