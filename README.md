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
     ```bash
     pip install -r requirements.txt

3. **Run the notebook for training** 
     ```bash
     jupyter notebook SpeechEmotionRecognition.ipynb


## 📂 Project Structure
 ```bash
speech-emotion-recognition/
│-- data/                  # Dataset (RAVDESS)
│-- models/                # Saved models
│-- SpeechEmotionRecognition.ipynb  # Training Notebook
│-- app.py                 # Gradio app for deployment
│-- requirements.txt       # Dependencies
│-- README.md              # Project documentation
 ```

## 🔧 Configuration

- Dataset: RAVDESS
- Sample rate: 22050 Hz
- Features extracted: MFCCs, Chroma, ZCR, Spectral Contrast, Tonnetz

## 🧪 Testing

- Tested on RAVDESS dataset (speech subset)
- Achieved 54%+ accuracy on test set

## 📊 Results

- Achieved 54%+ test accuracy on the RAVDESS dataset
- Deployed an interactive Gradio app for real-time voice emotion detection

## 👨‍💻 Authors / Credits

- Developed by Shrunkhala Sisodia
- 🎓 Master’s in Business Intelligence & Analytics
- 🌍 Location: Ahmedabad, India
- 🔗[LinkedIn](https://www.linkedin.com/in/shrunkhalasandeepsisodia/)
- Dataset: RAVDESS

## 📌 Future Improvements

- Improve accuracy by experimenting with CNN/LSTM models
- Test on larger and diverse datasets
- Integrate with a real-time speech recognition pipeline 

