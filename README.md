# vocalpathdetection
Vocal Pathology Detection using Feature Extraction and Machine Learning
Vocal Pathology Detection

A machine learning-based project to detect pathological voice conditions using vocal features extracted from audio signals.

Table of Contents
1. Introduction
2. Features
3. Technologies Used
4. Installation
5. Usage
6. Dataset
7. Model Training and Evaluation
8. Results
9. License
10. Acknowledgments



*Introduction*

This repository implements a machine learning solution to detect pathological voice conditions using audio recordings. The system analyzes vocal features and classifies voices into pathological or healthy categories.


*Features*

Extracts acoustic features such as jitter, shimmer, and MFCCs.
Uses advanced machine learning models like Support Vector Machine (SVM), Gaussian Mixture Models (GMM), and Random Forest Classifier (RFC).
Provides insights into vocal health based on audio analysis.


*Technologies Used*

Programming Languages: Python
Python: NumPy, Pandas, Scikit-learn, Librosa, Matplotlib
Machine Learning Models: SVM, GMM, RFC


*Installation*

1. Clone this repository:
```bash
git clone https://github.com/<your-username>/vocal-pathology-detection.git  
cd vocal-pathology-detection  
```

2. Install the required Python packages:
```bash
Copy code
pip install -r requirements.txt  
```


*Usage*
1. Preprocess the dataset:
Ensure the audio files are in the correct format. Run the preprocessing script to extract features:

```bash
python extract_features.py  
```

2. Train the model:
```bash
python train_model.py  
```

3. Test the model:
```bash
python test_model.py
```

4. Visualize the results:
```bash
python visualize_results.py
```


*Dataset*

The dataset used for this project consists of voice recordings from individuals with and without pathological conditions. [Provide details about dataset source or instructions for obtaining it.]



*Model Training and Evaluation*

The features are extracted from audio files using Librosa. Training and testing were performed using multiple classifiers. Evaluation metrics include accuracy, precision, recall, and F1-score.



*Results*



*License*

This project is licensed under the MIT License - see the LICENSE file for details.


*Acknowledgments*



*Dataset Source*

https://stimmdb.coli.uni-saarland.de/help_en.php4


*Advisor*

Dr. Ananya Bonjyotsna, Assistant Professor, Department of ECE, Tezpur University
