# EEG-Based Driver Fatigue Detection

This project implements a **Machine Learning pipeline** to detect driver fatigue using EEG signals. It uses the publicly available dataset from [Figshare](https://figshare.com/articles/dataset/The_original_EEG_data_for_driver_fatigue_detection/5202739) which contains EEG recordings from twelve subjects driving under fatigue and normal conditions.

---

## Dataset

- **Source:** [Figshare EEG Driver Fatigue Dataset](https://figshare.com/articles/dataset/The_original_EEG_data_for_driver_fatigue_detection/5202739)
- **Description:** EEG recordings collected from 12 subjects under alert and fatigued driving conditions.

---

## Tech Stack

- **Language:** Python
- **Libraries:**
  - `mne` — EEG data loading & preprocessing
  - `scikit-learn` — Traditional ML models
  - `TensorFlow` — Deep Learning models (CNN, ANN)
- **Models Used:**
  - **Supervised ML:** Random Forest, Decision Tree, SVM
  - **Unsupervised ML:** k-NN clustering
  - **Deep Learning:** CNN, ANN

---

## Preprocessing

- EEG signals were preprocessed using **MNE-Python**:
  - Filtering & noise removal
  - Epoch extraction
  - Feature extraction (time & frequency domain features)
  - PCA was used for dimensionality reduction

---

## Model Training

- Multiple supervised ML models were trained and evaluated.
- An unsupervised **k-NN clustering** was explored to group EEG patterns.
- Deep learning architectures (**CNN**, **ANN**) were implemented using TensorFlow to learn complex EEG signal representations.

---

## Results

- Achieved a **highest accuracy of 99.4%** using the CNN model.
- Traditional ML models like Random Forest and SVM also performed strongly on the preprocessed features.

---



