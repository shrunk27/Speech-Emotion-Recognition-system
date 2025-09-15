# 🎙️ Speech Emotion Recognition using ANN  

## 📌 Project Overview  
This project focuses on **Speech Emotion Recognition (SER)** using an **Artificial Neural Network (ANN)**.  
The system classifies human emotions (such as *happy, sad, angry, fearful, etc.*) from speech signals by extracting relevant audio features.  

It leverages the **RAVDESS dataset** for training and uses **Librosa** for feature extraction, **TensorFlow/Keras** for deep learning, and **Gradio** for deployment.  

---

## ⚡ Key Features  
- 🎵 **Audio Feature Extraction**: MFCCs, Chroma, Zero Crossing Rate, Spectral Contrast, and Tonnetz  
- 🧠 **Deep Learning Model**: Artificial Neural Network (ANN) with TensorFlow/Keras  
- 📊 **Model Performance**: Achieved **54%+ test accuracy** on emotion classification  
- 🌐 **Deployment**: Interactive Gradio interface for real-time emotion recognition  
- 📂 **Dataset**: RAVDESS Emotional Speech Dataset  

---

## 🛠️ Tech Stack  
- **Programming Language**: Python  
- **Libraries**: TensorFlow, Keras, Scikit-learn, Librosa, Pandas, NumPy, Matplotlib, Seaborn, Gradio  
- **Tools**: Jupyter Notebook, GitHub  

---

## 🚀 How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/speech-emotion-recognition.git
   cd speech-emotion-recognition

2. **Install dependencies** 
    pip install -r requirements.txt

3. **Run the notebook for training** 
    jupyter notebook SpeechEmotionRecognition.ipynb

## 📊 Results

- Achieved 54%+ test accuracy on the RAVDESS dataset
- Deployed an interactive Gradio app for real-time voice emotion detection

## 📌 Future Improvements

- Improve accuracy by experimenting with CNN/LSTM models
- Test on larger and diverse datasets
- Integrate with a real-time speech recognition pipeline 

