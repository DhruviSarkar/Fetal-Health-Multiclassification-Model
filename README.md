# Fetal-Health-Multiclassification-Model
This project uses machine learning to predict fetal health status (Normal, Suspect, or Pathological) based on Cardiotocography (CTG) data. The goal is to demonstrate how data science can support early detection of risks during pregnancy and potentially assist clinicians in decision-making.
## Dataset
- Source: Fetal Health Classification Dataset on Kaggle 
- Samples: 2,126 CTG records
- Features: 21 (fetal heart rate metrics, histogram features, etc.)
- Target: fetal_health
  - 1 → Normal
  - 2 → Suspect
  - 3 → Pathological
## Workflow
- Data Preprocessing
    - Split dataset into features (X) and labels (y)
    - Train/test split (80/20)
    - Standardization of features
- Model Training
    - Logistic Regression (baseline model)
    - Multiclass classification
- Evaluation
    - Accuracy score
    - Classification report (precision, recall, F1-score)
## Results
- Achieved ~90% accuracy on the test set.
- Model performs well in distinguishing Normal vs. Suspect vs. Pathological fetal health conditions.
## How to Run
1. Clone this repo:
```bash
git clone https://github.com/your-username/fetal-health-classification.git
cd fetal-health-classification
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the notebook or script to train/test the model.
