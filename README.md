# SVM – Breast Cancer Classification

## Objective
Build a Support Vector Machine (SVM) model to classify breast cancer tumors as malignant or benign.

## Dataset
- Sklearn Breast Cancer Dataset (`load_breast_cancer()`)

## Tools Used
- Python
- Scikit-learn
- Matplotlib

## Workflow
1. Loaded and explored dataset
2. Applied feature scaling using StandardScaler
3. Trained SVM with Linear and RBF kernels
4. Tuned hyperparameters using GridSearchCV
5. Evaluated model using confusion matrix and classification report
6. Plotted ROC curve and calculated AUC score
7. Saved final trained model pipeline

## Results
- Best kernel: RBF
- High classification accuracy
- AUC score close to 1.0 indicating strong performance

## Files
- `svm_breast_cancer.ipynb` – notebook
- `svm_breast_cancer_model.pkl` – saved model
##Author
Mrunal Arote
## Learning Outcome
Learned kernel-based classification, hyperparameter tuning, and ROC-AUC evaluation using SVM.
