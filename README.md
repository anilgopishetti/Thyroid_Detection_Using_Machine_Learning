#  Thyroid Disease Prediction Using Machine Learning

A machine learning-based application to predict the presence of thyroid disease using patient data. This project aims to assist medical professionals by providing intelligent insights for early diagnosis and treatment.



##  Features
- Trains machine learning models on thyroid-related health data
- Preprocessing pipeline for handling missing and categorical values
- Exploratory data analysis and visualization
- Predictions on new patient data
- Batch inference using `testData.csv`
- Model accuracy and performance metrics

##  Dataset
- *hypothyroid.csv*: Main dataset containing clinical and diagnostic features.
- **testData.csv**: Sample test data for inference.

##  Tech Stack
- Python 3.x
- Scikit-learn
- Pandas & NumPy
- Matplotlib / Seaborn
- Jupyter / Streamlit (if used)
- GitHub Actions (CI workflows)

##  Project Structure
```
Thyroid_Detection_Using_Machine_Learning/
├── ThyroidDisease/
│   ├── ThyroidDiseaseDetection.py
│   ├── requirements.txt
│   ├── run.bat
│   └── ... 
├── hypothyroid.csv
├── testData.csv
├── thyroidcode (possibly compiled file or script)
└── .github/
    └── workflows/
        ├── jekyll-gh-pages.yml
        └── static.yml
```

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/anilgopishetti/Thyroid_Detection_Using_Machine_Learning.git
cd Thyroid_Detection_Using_Machine_Learning/ThyroidDisease
```

### 2. Install Dependencies
``
pip install -r requirements.txt
``

### 3. Run the Model
`
python ThyroidDiseaseDetection.py
`

> Optionally, use `run.bat` if on Windows to execute the script.

##  Results
- Accuracy: _[Insert Model Accuracy]_%
- Confusion Matrix, Precision, Recall, F1 Score metrics can be added here.

##  Contributing
Contributions are welcome! Please fork this repository and submit a pull request.

##  License
This project is licensed under the MIT License.

##  Contact
Developed by ** Gopishetti Anil **  
Email: gopishettianil6@gmail.com

