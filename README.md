## Project Overview

The **Student Performance Prediction ML Project** is designed to:
- Perform exploratory data analysis (EDA) to understand the dataset.
- Process and transform data for machine learning models.
- Train and optimize models, with a focus on CatBoost for accurate predictions.
- Provide a web interface for predictions, making it accessible for real-world applications.

---

## Features

- **Exploratory Data Analysis:** Insights into the data using Jupyter Notebooks.
- **Data Ingestion, Transformation, and Model Training Pipelines:** Modularized pipeline for seamless ML workflows.
- **CatBoost Integration:** Robust gradient-boosting model for performance prediction.
- **Web Deployment:** A user-friendly interface for real-time student performance prediction.

---

## Directory Structure

```plaintext
rahulkothuri-student-performance-ml-project/
├── README.md                # Project documentation
├── application.py           # Main Flask application
├── requirements.txt         # Python dependencies
├── setup.py                 # Setup script for deployment
├── artifacts/               # Directory for storing artifacts like models
├── catboost_info/           # Logs and training details of CatBoost
│   ├── catboost_training.json
│   ├── learn_error.tsv
│   ├── time_left.tsv
│   └── learn/
│       └── events.out.tfevents
├── notebook/
│   ├── EDA.ipynb            # Exploratory Data Analysis notebook
│   └── data/
│       └── stud.csv         # Dataset file
├── src/                     # Source code for ML pipelines and utilities
│   ├── __init__.py
│   ├── exception.py         # Custom exception handling
│   ├── logger.py            # Logging setup
│   ├── utils.py             # Utility functions
│   ├── components/
│   │   ├── __init__.py
│   │   ├── data_ingestion.py # Data ingestion logic
│   │   ├── data_transformation.py # Data preprocessing and transformation
│   │   └── model_trainer.py  # Model training logic
│   └── pipeline/
│       ├── __init__.py
│       ├── predict_pipeline.py # Prediction pipeline
│       └── train_pipeline.py  # Training pipeline
├── templates/
│   ├── home.html            # Landing page
│   └── index.html           # Prediction page
└── .ebextensions/
    └── python.config        # AWS Elastic Beanstalk configuration
```
    
