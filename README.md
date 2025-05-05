## 🧠 EEG Data Analysis and Alcoholism Detection Using Machine Learning (2024)

### 📌 Project Summary

* Transformed raw EEG signals into **time-frequency spectrograms** to enable visual learning-based classification of subjects as **alcoholic or non-alcoholic**.
* Developed a **hybrid CNN-SVM pipeline**, where deep features extracted from a Convolutional Neural Network were passed to an SVM classifier.
* Achieved **over 90% accuracy** in subject classification, demonstrating strong potential for non-invasive neurological screening.

---

### 📁 Dataset Overview

The EEG data used in this project comes from **physiological recordings of alcoholic and control subjects** during visual stimuli tasks. Each sample contains multiple EEG channel signals recorded over time.

* 📊 **Source**: [EEG Spectrogram Images on Kaggle](https://www.kaggle.com/datasets/sayeemmohammed/eeg-spectrogram-images)
* 🧠 **Data Type**: Multi-channel EEG signals converted into **spectrogram images**
* 🔢 **Classes**:

  * **Alcoholic**
  * **Non-Alcoholic**
* ⚙️ **Preprocessing**:

  * Applied signal filtering
  * Generated spectrograms using Short-Time Fourier Transform (STFT)
  * Normalized and resized all images for CNN input
