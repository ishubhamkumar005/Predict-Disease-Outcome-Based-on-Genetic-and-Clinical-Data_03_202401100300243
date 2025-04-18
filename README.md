# Predict-Disease-Outcome-Based-on-Genetic-and-Clinical-Data_03_202401100300243

AutoML Patient Segmentation Analysis
This project provides an automated machine learning pipeline for patient segmentation and classification using a Random Forest classifier and KMeans clustering.

Features
Automated data preprocessing and cleaning

Target variable auto-selection

Categorical feature encoding

Feature scaling

Random Forest classification

KMeans clustering

PCA visualization

Performance metrics reporting

Requirements
Python 3.7+

pandas

numpy

scikit-learn

seaborn

matplotlib

Usage
Run the script in a Python environment (Google Colab recommended)

Upload your dataset when prompted

The script will automatically:

Clean the data

Select a target variable

Preprocess features

Train a classification model

Perform clustering

Generate visualizations

Outputs
Classification metrics (accuracy, precision, recall)

Confusion matrix heatmap

PCA visualization of patient clusters

Customization
To modify the analysis:

Change test_size in train_test_split for different validation splits

Adjust n_clusters in KMeans for different segmentation

Modify visualization parameters as needed

Example Output
Copy
📂 Upload your dataset...
✅ Auto-selected 'diagnosis' as the target column.

📊 Evaluation Metrics:
✅ Accuracy : 0.9234
✅ Precision: 0.9142
✅ Recall   : 0.9018
