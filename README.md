# <div align="center">BF1Kart</div>

## 📋 Project Overview

BF1Kart is a data mining project developed for BestFinansBir (BF1) to optimize credit card marketing campaigns. The model predicts customer likelihood to purchase the new BF1Kart credit card, enabling targeted marketing efforts and cost reduction.

The solution employs Random Forest classification, trained on partner company data with similar customer structure, to identify high-potential customers for marketing outreach.


## 🎯 Project Objectives
- Develop high-accuracy classification model for credit card purchase prediction
- Reduce customer acquisition costs and optimize marketing resource allocation
- Enable data-driven marketing decisions

## 🔍 Dataset Description

### Data Source
- Dataset: BestFinansBir_v1.0.csv
- Data points count: 20493

### Features
| Feature | Description | Type |
|---------|-------------|------|
| ID | Customer Unique Identifier | Numeric |
| Alter (Age) | Customer's Age | Numeric |
| Beruf (Occupation) | Employee etc. | Categorical |
| Familienstand (Marital Status) | Single, married or divorced | Categorical |
| Ausbildung (Education Level) | university degree, general university entrance qualification, etc. | Categorical |
| Ausgefallen (Default Status) | Indicates whether the customer has failed | Binary |
| Kontostand (Account Balance) | Account balance on the date the data was extracted | Numeric |
| Eigentum (Property Ownership) | Indicates whether the customer owns a property {1: Yes, 0: No} | Binary |
| Darlehen (Loan Status) | Indicates whether the customer has loan obligations {1: Yes, 0: No} | Binary |
| Dauer (Relationship Duration) | Duration of the business relationship in days | Numeric |
| Label (Target) | Indicates whether the customer has purchased the advertised banking product {1: Yes, 0: No} | Binary |

## 🛠 Technical Implementation

### Model Architecture
- Algorithm: Random Forest Classifier
- Train/Test Split: 70/30
- Random Seed State: 4711

### Project Phases
1. **Data Understanding**
   - Feature analysis
   - Distribution examination
   - Correlation studies

2. **Data Preprocessing**
   - Missing value handling
   - Feature encoding
   - Data normalization
   - Data splitting for training and testing

3. **Modeling**
   - Random Forest implementation
   - Hyperparameter optimization
   - Cross-validation

4. **Evaluation**
   - Confusion Matrix
   - Accuracy metrics
   - Precision & Recall analysis
   - XAI implementation

## 📈 Performance Metrics
- Primary Metric: Recall fits better than Accuracy in our case!
- Measured Metrics:
  - Precision
  - Recall
  - Accuracy
  - F1-Score
  - ROC-AUC
- Explainable AI Analysis: Permutation Importance, Partial Dependence, SHAP (SHapley Additive exPlanations) 

## 🚀 Installation

### Prerequisites
- Python 3.x
- Required libraries: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - eli5
  - pdpbox
  - shap

### Setup
```bash
git clone https://github.com/odabashi/BF1Kart.git
cd BF1Kart
```
<p align="center"> 
    Found value here? A quick upvote supports continued research and sharing! 👍
</p> 
