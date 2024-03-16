<h1>**Breast Cancer Patient Survival Prediction**</h1>
This Python script analyzes breast cancer patient data from the provided CSV file ("BRCA.csv") and builds a Support Vector Machine (SVM) model to predict patient survival status based on various features.

<h1>**Usage:**</h1>
Ensure Python environment with required libraries (Pandas, NumPy, Plotly, Scikit-learn) is set up.
Place the dataset file "BRCA.csv" in the same directory as the script.
Run the script to execute the analysis and prediction.
Modify the 'features' array to input different patient features for prediction.


<h1>**Dependencies:**</h1>
Python 3
Pandas
NumPy
Plotly
Scikit-learn


<h1>**Features Explored:**</h1>
Gender
Tumour Stage
Histology
ER status
PR status
HER2 status
Type of Surgery


<h1>**Data Transformation**</h1>
Categorical variables are mapped to numerical representations for modeling purposes.


<h1>**Model Training:**</h1>
The script initializes and trains a Support Vector Machine (SVM) model using Scikit-learn's SVC.


<h1>**Prediction:**</h1>
The trained model performs predictions on sample features representing a patient and displays the predicted patient survival status.


**Note: This script assumes the presence of the dataset file "BRCA.csv" in the same directory. Users can modify the feature mapping and adjust the model parameters as needed for their specific analysis. **
