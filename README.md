# fetal-health-classification.
This project demonstrates fetal health classification using machine learning. The dataset includes medical features. Python with pandas and scikit‑learn was used for preprocessing, scaling, and training a Random Forest classifier. Evaluation was done with confusion matrix, classification report, and heatmap. Results saved to a text file.
# Fetal Health Classification using Random Forest

## ⚙️ Steps

1. **Libraries Used**
   - pandas, numpy → data handling
   - scikit-learn → preprocessing, training, evaluation
   - matplotlib, seaborn → visualization

2. **Dataset**
   - File: `fetal_health.csv`
   - Target variable: `fetal_health` (3 classes)

3. **Preprocessing**
   - Train-test split (80:20)
   - Feature scaling using StandardScaler

4. **Model Training**
   - Algorithm: RandomForestClassifier
   - Random state fixed for reproducibility

5. **Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

6. **Visualization**
   - Confusion Matrix Heatmap using seaborn

7. **Documentation**
   - Results saved in `report.txt`


## 📊 Results
- High accuracy (~94–96%)
- Balanced performance across all three classes
- Confusion Matrix and Classification Report show strong precision and recall


## ✅ Conclusion
Random Forest is effective for fetal health classification.  
This project demonstrates a complete ML pipeline: preprocessing, training, evaluation, visualization, and documentation.

## 📂 Files
- `fetal_health.csv` → Dataset  
- `fetal_health.py` → Code  
- `report.txt` → Evaluation results  


## ▶️ How to Run
```bash
# Clone the repository
git clone https://github.com/YourUsername/fetal-health-classification.git

# Navigate to folder
cd fetal-health-classification

# Run the script
python fetal_health.py
