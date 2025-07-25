# AI-Enhanced Intrusion Detection System (IDS)  
### Cybersecurity Threat Detection Using Machine Learning

## Project Description
This project develops an AI-Enhanced Intrusion Detection System using a Random Forest Classifier to detect and classify network intrusions with high accuracy. It integrates machine learning with cybersecurity expertise to proactively combat evolving threats.

## Technologies Used
- Python 3.10+
- Flask (Backend)
- HTML/CSS (Frontend)
- Pandas/NumPy (Data Manipulation)
- Scikit-learn (Machine Learning)
- Imbalanced-learn (SMOTE for Class Balancing)
- Joblib (Model Serialization)

## Model Details
The system uses a Random Forest Classifier trained on a balanced dataset with SMOTE to address class imbalance. The trained model is saved as `random_forest_model_4_features.joblib`.

## Project Directory Structure
```
AI-ENHANCED-INTRUSION-DETECTION/
├── CYBER_PROJECT/
│   ├── templates/
│   │   └── index.html               # Web interface template
│   ├── app.py                       # Flask application
│   ├── random_forest_model_4_features.joblib
│   ├── web_attacks_balanced.csv     # Preprocessed dataset
│   ├── requirment.txt               # Python dependencies
│   ├── Untitled.ipynb               # Analysis notebook
│   └── README.md                    # Project documentation
├── Documentation/
└── README.md
```

## Installation & Setup
### Using Conda (Recommended)
```bash
conda create -n cyber_ids python=3.10
conda activate cyber_ids
git clone https://github.com/Rohitmh09/AI-Enhanced-Intrusion-Detection-System.git
cd CYBER_PROJECT
pip install -r requirment.txt
```

### Using Python venv
```bash
python -m venv ids_env
# Windows: ids_env\Scripts\activate
# macOS/Linux: source ids_env/bin/activate
pip install -r requirment.txt
```

## Running the Application
```bash
cd CYBER_PROJECT
python app.py
```
Open your browser and navigate to:  
[http://127.0.0.1:5000/](http://127.0.0.1:5000/)

## Dataset Overview
The `web_attacks_balanced.csv` dataset contains labeled network traffic data, categorized into intrusions and normal behavior.

## Conclusion
This AI-powered IDS leverages machine learning to enable real-time intrusion detection, reducing response time and enhancing organizational cybersecurity.