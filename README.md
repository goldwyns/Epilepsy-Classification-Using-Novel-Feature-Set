# EEG Signal Classification and Clustering

This project focuses on the analysis and classification of EEG signals using advanced machine learning techniques. The aim is to extract meaningful insights from EEG data and apply supervised and unsupervised learning models for classification and clustering.

## Features
- **Data Preprocessing**: Includes detrending, bandpass filtering, normalization, and segmentation of EEG signals.
- **Feature Extraction**: Extracts statistical, LPC, cepstral, lattice, inverse filtering, and spectral features from EEG segments.
- **Supervised Learning**: Implements and compares multiple neural network architectures:
  - LSTM
  - Bi-LSTM
  - GRU
  - Transformer
- **Unsupervised Learning**: Utilizes clustering algorithms such as:
  - K-Means
  - Hierarchical Clustering
  - DBSCAN
  - Gaussian Mixture Model
- **Performance Evaluation**: Provides comprehensive metrics like accuracy, sensitivity, specificity, F1-score, Matthews Correlation Coefficient, AUC, and silhouette scores.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/eeg-signal-classification.git
/content/drive/MyDrive/Database/Bonn Univ Dataset/
├── s/
├── z/
├── o/
├── f/
└── n/
python classify_eeg.py
python cluster_eeg.py
eeg-signal-classification/
├── data/                      # Contains EEG datasets
├── models/                    # Neural network and clustering models
├── feature_extraction.py      # Functions for feature extraction
├── preprocess.py              # Functions for data preprocessing
├── classify_eeg.py            # Supervised classification script
├── cluster_eeg.py             # Unsupervised clustering script
└── README.md                  # Project documentation
Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

License
This project is licensed under the MIT License. See LICENSE for more details.

Acknowledgments
EEG datasets are sourced from the Bonn University Dataset.
