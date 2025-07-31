# MLAssignment3
Cat vs Dog Image Classification Project
=======================================

Project Description:
-------------------
This project implements two deep learning models for classifying images of cats and dogs:
1. Custom CNN built from scratch
2. Transfer learning using VGG16 with fine-tuning

Requirements:
------------
Python 3.8+ with these packages:
- tensorflow==2.12.0
- keras==2.12.0
- numpy==1.23.5
- pandas==1.5.3
- matplotlib==3.7.1
- seaborn==0.12.2
- jupyter==1.0.0
- scikit-learn==1.2.2

Installation:
-----------
1. Create and activate virtual environment:
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate    # Windows

2. Install requirements:
   pip install -r requirements.txt

Dataset Setup:
------------
1. Download dataset from Kaggle:
   https://www.kaggle.com/c/dogs-vs-cats/data

2. Extract to create this structure:
   data/
   └── train/
       ├── cat.0.jpg
       ├── cat.1.jpg
       ├── ...
       ├── dog.0.jpg
       └── dog.1.jpg

How to Run:
---------
Option 1: Jupyter Notebook
   jupyter notebook Cat_Dog_Classification.ipynb

Option 2: Command Line
   python train.py --model cnn --epochs 30

Project Structure:
----------------
.
├── data/            # Training images
├── models/          # Saved models
├── notebooks/       # Jupyter notebooks
├── src/             # Python scripts
│   ├── train.py     # Training script
│   └── utils.py     # Helper functions
├── requirements.txt # Dependencies
└── README.md        # This file

Results:
-------
| Model          | Accuracy | Training Time |
|----------------|----------|---------------|
| Custom CNN     | 85%      | 45 minutes    |
| VGG16          | 92%      | 90 minutes    |

License:
-------
MIT License

Contact:
-------
For questions: your.email@example.com
