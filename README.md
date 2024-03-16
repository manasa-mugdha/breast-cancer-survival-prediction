##**Breast Cancer Patient Survival Prediction**
This Python script analyzes breast cancer patient data from the provided CSV file ("BRCA.csv") and builds a Support Vector Machine (SVM) model to predict patient survival status based on various features.

##**Usage:**
Ensure Python environment with required libraries (Pandas, NumPy, Plotly, Scikit-learn) is set up.
Place the dataset file "BRCA.csv" in the same directory as the script.
Run the script to execute the analysis and prediction.
Modify the 'features' array to input different patient features for prediction.


##**Dependencies:**
Python 3
Pandas
NumPy
Plotly
Scikit-learn


##**Features Explored:**
Gender
Tumour Stage
Histology
ER status
PR status
HER2 status
Type of Surgery


##**Data Transformation**
Categorical variables are mapped to numerical representations for modeling purposes.


##**Model Training:**
The script initializes and trains a Support Vector Machine (SVM) model using Scikit-learn's SVC.


##**Prediction:**
The trained model performs predictions on sample features representing a patient and displays the predicted patient survival status.


**Note: This script assumes the presence of the dataset file "BRCA.csv" in the same directory. Users can modify the feature mapping and adjust the model parameters as needed for their specific analysis. **
