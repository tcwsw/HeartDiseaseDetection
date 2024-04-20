# SC1015 Data Science Project - Heart Disease
## Installation and Running
1. Installation
```
git clone https://github.com/tcwsw/HeartDiseaseDetection.git
cd HeartDiseaseDetection
```
2. Install Package
```
conda create -n heart python=3.12 -y
conda activate heart
pip install -e .
```
a conda environment will be made with the libraries in requirements.txt

3. Running in VScode (if you prefer)
```
code .
```
The first import will take about 30secs, this code is tested in VScode.

## Dataset Link
[Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## Presentation Slides Link
[Google Slides Presentation](https://docs.google.com/presentation/d/1Ku_PUJqqGOFjxNU-jKybwTMmdZDY2e-y1vyrpaYHzBE/edit?usp=sharing)

### Motivation
Heart disease is a prevalent issue and severely impacted our lives. This can also be seen from statistics provided by Singapore Heart Foundation that 23 people die from heart disease everyday. 

### Objective
Our team aims to address the heart disease problem in Singapore by predicting the likelihood of a person developing heart disease and providing preventive measures.

### Entire Codebase Sequence
1. Brief Introduction to the Dataset
2. Import Necessary Modules
3. Basic Preprocessing of the Dataset
4. Correction of Errors in the Dataset
5. Exploratory Data Analysis (EDA)
6. Machine Learning Models
   - Linear Regression
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Perceptron
7. Inference (User is able to enter their own health data and get a predicted result using perceptron model)
8. Analysis and Evaluation (Outcome) - Incorporated inside ML models
9. Data-Driven Insights and Recommendations - Incorporated inside EDA and ML models

### References
- [SingHealth](https://www.singhealth.com.sg/patient-care/conditions-treatments/cardiovascular-disease)
- [MyHeart.org.sg](https://www.myheart.org.sg/health/heart-disease-statistics/)

### Individual Contribution
- **Bryan**:
  - Data Preprocessing
  - EDA
  - Decision Tree
  - Perceptron
  - Inference
- **Siwen**:
  - Data Preprocessing
  - Linear & Logistic Regression
  - Slides
  - Readme


