# Heart Attack Analysis & Prediction Dataset (Kaggle)
Dave Kramer (2021)

## Welcome to this project on Heart Attack Analysis & Prediction

## Description
As heart attacks in younger people are becoming more common I was interested in trying to predict whether on not someone will have heart disease based on serveral factors related to their current health and other heart realted issues.
I've chosen the dataset from Kaggle (https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset/).


## Data Analysis
There are a couple columns that are not self-explanatory so here is some more information.

  - age: The person's age in years
  - sex: The person's sex (1 = male, 0 = female)
  - cp: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
  - trtbps: The person's resting blood pressure (in mm Hg)
  - chol: The person's cholestoral in mg/dl fetched via BMI sensor
  - fbs: The person's fasting blood sugar (&gt; 120 mg/dl, 1 = true; 0 = false)
  - restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
  - thalachh: The person's maximum heart rate achieved
  - oldpeak: ST depression induced by exercise relative to rest
  - slp: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
  - caa: The number of major vessels (0-3)
  - thall: A blood disorder called thalassemia Value 0: NULL (dropped from the dataset previously Value 1: fixed defect (no blood flow in some part of the heart) Value 2: normal blood flow Value 3: reversible defect (a blood flow is observed but it is not normal)
  - exng: Exercise induced angina (1 = yes; 0 = no)
  - target: Heart disease (0 = no, 1 = yes)

## Libraries
I'm used the following libraries:

  - Pandas
  - Numpy
  - Matplotlib
  - SKLearn
  - Seaborn

## Running the code
This is an executable Jupyter notebook.

### Option 1 - Using a free online resource
Run the notebook on mybinder.org, a free online service for running Jupyter notebooks - however you can also select "Run on Colab" or "Run on Kaggle".

### Option 2 - Running on your computer
Install Conda on your computer use the following link (https://conda.io/projects/conda/en/latest/user-guide/install/index.html) - download the files and open them in your editor.