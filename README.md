# Parkinson’s Disease Prediction using Machine Learning

## Overview:
This project applies machine learning techniques to classify individuals as Parkinson’s disease patients or healthy controls using biomedical voice measurements.

## Clinical Relevance
Parkinson’s disease is a progressive neurodegenerative disorder where early diagnosis is crucial. Traditional diagnostic methods can be subjective, whereas acoustic analysis of voice recordings offers a non-invasive, objective, and cost-effective approach for early detection.

This project explores how vocal biomarkers can be used for automated disease classification.

## Dataset:
The dataset consists of biomedical voice measurements from individuals with and without Parkinson’s disease. Each instance represents a voice recording, with multiple numerical features capturing vocal characteristics.

Target variable:
- `0` → Healthy
- `1` → Parkinson’s Disease
  
## Methods:
- Data preprocessing and cleaning
- Removal of non-informative features (e.g., identifiers)
- Feature scaling using StandardScaler
- Train-test split for model evaluation
- Logistic Regression for classification

## Results
The model demonstrated high sensitivity (recall), successfully identifying all Parkinson’s cases in the test set, with a small number of false positives.

This is particularly important in clinical settings, where failing to detect a disease (false negative) is more critical than over-diagnosis.

## Tools & Technologies:
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

## Repository Structure
- `parkinson_disease_ML_Project.ipynb` – main notebook
- `confusion_matrix.png` – model evaluation

## Future Work
This project can be extended by integrating multimodal data sources such as neuroimaging (MRI), genomic data, or longitudinal clinical records. Combining multiple data modalities could improve predictive accuracy and provide deeper insights into neurodegenerative disease progression.

## Dataset License and Attribution

This project uses the **Oxford Parkinson’s Disease Detection Dataset**, licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).

**Original authors:**
Little, M. A., McSharry, P. E., Hunter, E. J., & Ramig, L. O. (2008)

**Source:**  
UCI Machine Learning Repository  

**License:**  
https://creativecommons.org/licenses/by/4.0/
