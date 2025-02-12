# 🚀 Machine Learning Model Automation & Versioning  

## 📌 Project Overview  
This project automates the process of training, testing, and versioning a **Machine Learning model**. It allows you to:  

✅ Load a dataset (default: **Iris dataset**)  
✅ Preprocess data (handle missing values, normalize, encode categorical features)  
✅ Train a **Random Forest Classifier** (can be modified)  
✅ Evaluate model performance using **accuracy, precision, recall, and F1-score**  
✅ Save the trained model in a **version-controlled** format  
✅ Track model improvements over time with **auto-incremented versioning**  

---

## 🛠 Tech Stack  
- **Python 3.8+**  
- **Scikit-Learn** (Machine Learning)  
- **Pandas, NumPy** (Data Processing)  
- **Joblib** (Model Saving)  
- **JSON** (Metadata Tracking)  

---

## 📥 Installation & Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/your-username/ML_Model_Automation.git
cd ML_Model_Automation
```
### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```
### 3️⃣ Run the Model Training Script
```sh
python main.py
```
## 🔍 How It Works?  

### 1️⃣ Load Dataset  
- **Default:** Iris dataset  
- You can replace it with any dataset (modify `main.py` accordingly).  

### 2️⃣ Data Preprocessing  
- **Feature Scaling** (`StandardScaler`)  
- **Train-Test Split (80-20%)**  

### 3️⃣ Train Model  
- **Default:** Random Forest Classifier  
- Can be replaced with **XGBoost, SVM, Neural Networks, etc.**  

### 4️⃣ Evaluate Performance  
- **Accuracy, Precision, Recall, F1-score**  

### 5️⃣ Auto-Versioning & Model Saving  
- Model is saved in `/models/` directory with **auto-incremented versions** (`model_v1.pkl`, `model_v2.pkl`, etc.)  
- **Metadata (`metadata.json`) is updated** with model performance details.  

---

## 🔄 Future Enhancements  
- **Hyperparameter Tuning** (`GridSearchCV`)  
- **Experiment with Different Models**  
- **Deploy Model as an API** (`FastAPI / Flask`)  
- **Use Cloud Storage** (`AWS S3`, `Google Drive`) for **Model Versioning**  

---

## 📜 License  
This project is **open-source** under the **MIT License**.  


 
