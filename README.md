<h1>Breast Cancer Patient Survival Prediction</h1>
This Python script analyzes breast cancer patient data from the provided CSV file ("BRCA.csv") and builds a Support Vector Machine (SVM) model to predict patient survival status based on various features.

<h2>Usage:</h2>
Ensure Python environment with required libraries (Pandas, NumPy, Plotly, Scikit-learn) is set up.
Place the dataset file "BRCA.csv" in the same directory as the script.
Run the script to execute the analysis and prediction.
Modify the 'features' array to input different patient features for prediction.


<h2>Dependencies:</h2>
Python 3
Pandas
NumPy
Plotly
Scikit-learn


<h2>Features Explored:</h2>
Gender
Tumour Stage
Histology
ER status
PR status
HER2 status
Type of Surgery


<h2>Data Transformation</h2>
Categorical variables are mapped to numerical representations for modeling purposes.


<h2>Model Training:</h2>
The script initializes and trains a Support Vector Machine (SVM) model using Scikit-learn's SVC.


<h2>Prediction:</h2>
The trained model performs predictions on sample features representing a patient and displays the predicted patient survival status.


**Note: This script assumes the presence of the dataset file "BRCA.csv" in the same directory. Users can modify the feature mapping and adjust the model parameters as needed for their specific analysis. **
