# Audio Classification Model with STFT and TensorFlow  

This project demonstrates how to build an **audio classification model** using **Short-Time Fourier Transform (STFT)** and **TensorFlow**. The model processes audio signals, converts them into spectrograms, and classifies them into different categories using deep learning techniques.  

## 🔹 Overview  
- **Dataset**: ESC-50 (or any environmental sound dataset)  
- **Feature Extraction**: Short-Time Fourier Transform (STFT) to generate spectrograms  
- **Model Architecture**: Convolutional Neural Network (CNN) using TensorFlow/Keras  
- **Objective**: Classify audio clips into predefined categories  

## 📌 Features  
✔ Converts raw audio signals into frequency-time representations (spectrograms)  
✔ Uses STFT instead of Mel spectrograms for better frequency resolution  
✔ Built with TensorFlow for deep learning-based classification  
✔ Achieves high accuracy on environmental sound classification  


## 🚀 Installation & Usage  

### Download the dataset
[https://medium.com/@deepthika.sivaram.edu/building-an-audio-classification-model-with-stft-and-tensorflow-531a64f4baa9#:~:text=ESC%2D50%20GitHub%20Repository](https://github.com/karolpiczak/ESC-50)
### Clone the Repository  
```bash
git clone https://github.com/yourusername/Audio-Classification-STFT.git
cd Audio-Classification-STFT
```
Once the repository is cloned you can try the cells in Jupyter Notebook file individually to obtain results.

## 📈 Results

- Model achieves 80%+ accuracy on the ESC-50 dataset
- Performs well on real-world audio clips


## 🛠 Technologies Used
- Python
- TensorFlow/Keras
- Librosa (Audio Processing)
- Matplotlib & Seaborn (Visualization)
