# Data Dictionary

The original data came from the Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+Disease

There is also a version of it available on Kaggle. https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset

Below is a description of the key features used in the project:

- **age**: Age in years
- **sex**: (1 = male; 0 = female)
- **cp**: Chest pain type
  - 0: Typical angina (chest pain related to decreased blood supply to the heart)
  - 1: Atypical angina (chest pain not related to heart disease)
  - 2: Non-anginal pain (typically esophageal spasms)
  - 3: Asymptomatic (chest pain without disease symptoms)
- **trestbps**: Resting blood pressure in mm Hg on admission (concern if >130-140)
- **chol**: Serum cholesterol in mg/dl (concern if >200)
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg**: Resting electrocardiographic results
  - 0: Normal
  - 1: ST-T wave abnormality
  - 2: Left ventricular hypertrophy
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise-induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
  - 0: Upsloping (better heart rate with exercise)
  - 1: Flat (minimal change, typical healthy heart)
  - 2: Downsloping (unhealthy heart signs)
- **ca**: Number of major vessels (0-3) colored by fluoroscopy
- **thal**: Thalium stress test result
  - 1,3: Normal
  - 6: Fixed defect
  - 7: Reversible defect
- **target**: Presence of heart disease (1 = yes; 0 = no)

```{tableofcontents}
```