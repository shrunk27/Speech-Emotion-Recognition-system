# 🎤 Speech Emotion Recognition using ANN

This project is a Speech Emotion Recognition (SER) system that uses audio recordings to predict human emotions such as happy, sad, angry, etc. It is built using **Artificial Neural Networks (ANN)** with **MFCC and other audio features** extracted via `librosa`, trained on the **RAVDESS dataset**.

---

## 📁 Dataset

**RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**  
- [Download RAVDESS Dataset](https://zenodo.org/record/1188976)  
- Includes speech recordings of 24 professional actors expressing various emotions.  
- Emotions: `neutral`, `calm`, `happy`, `sad`, `angry`, `fearful`, `disgust`, `surprised`

---

## 🧠 Features Extracted

Using `librosa`, the following audio features are extracted:
- MFCC (Mel Frequency Cepstral Coefficients)
- Chroma STFT
- Zero Crossing Rate
- Spectral Contrast
- Tonnetz

Each audio file is transformed into a numerical feature vector for ANN input.

---

## 🏗️ Model Architecture

A simple ANN (fully-connected neural network) is used:
- Input: 68-dimensional feature vector
- Hidden layers: Dense layers with `ReLU` activation
- Output: Softmax layer with 8 emotion classes

---

## 🔧 Tools & Libraries

- Python
- `librosa` (feature extraction)
- `scikit-learn` (scaling, label encoding)
- `TensorFlow / Keras` (model building)
- `Gradio` (deployment interface)

---

## 📊 Accuracy

- **Training Accuracy**: ~85%  
- **Testing Accuracy**: ~54%  
(*Performance may improve with CNNs, data augmentation, or deeper architectures.*)

---

## 🚀 Deployment

The trained model is deployed using **Gradio**. You can upload any `.wav` file and get the predicted emotion.

## Credits
-Librosa
-RAVDESS Dataset
-TensorFlow
-Gradio

