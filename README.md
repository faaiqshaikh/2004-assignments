## Breast Cancer Classification ML Model
This machine learning model classifies breast cancer tumors as malignant or benign 
using the Random Forest algorithm. It is trained on the Breast Cancer Wisconsin (Diagnostic) dataset, 
which contains measurements of various features computed from fine needle aspirates (FNA) of breast masses.

### Features
"radius", "texture", "perimeter", "area", "smoothness", "compactness", "concavity", "concave_points", "symmetry", "fractal_dimension"

### Model Training and Evaluation
The dataset is split into training and testing sets (80:20 ratio). 
The Random Forest classifier with 100 estimators is trained on the training set and evaluated using accuracy, 
precision, recall, and F1-score metrics.
