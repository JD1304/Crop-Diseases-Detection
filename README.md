# Crop-Diseases-Detection-
## 🌾 Crop Disease Detection using Deep Learning | Streamlit Web App

This project is an AI-based crop disease detection system that utilizes deep learning to accurately identify plant diseases from leaf images. The model is built using a custom **ResNet9 architecture** and trained on a comprehensive dataset of crop disease images. It classifies 38 different plant disease categories, including both healthy and infected leaf conditions.

### 🔍 Features

- ✅ Deep learning model based on ResNet9 for high accuracy
- ✅ Classifies 38 plant diseases (including healthy class) across various crops
- ✅ Trained using PyTorch and optimized for real-world performance
- ✅ Exported in both `.h5` and `.tflite` formats for flexibility
- ✅ Easy-to-use **Streamlit web app** for real-time prediction
- ✅ User can upload leaf images and receive instant disease diagnosis
- ✅ Label mappings provided for clear interpretation of model predictions

### 🖥️ Technologies Used

- Python, PyTorch
- Google Colab for model training
- Streamlit for web app UI
- OpenCV & PIL for image preprocessing
- Matplotlib & Seaborn for data visualization

### 📁 File Structure

- `model/` – Trained model files
- `streamlit_app.py` – Web app source code
- `crop_disease_detection.ipynb` – Custom ResNet9 architecture
- `model_test`- For accuracy and analysis
- `utils/` – Image preprocessing and label mapping utilities
- `README.md` – Project overview

### 🚀 Getting Started

1. Clone the repo  
2. Install dependencies (`requirements.txt`)  
3. Run the Streamlit app:
   ```bash
   streamlit run streamlit_app.py
   ```
4. Upload an image of a crop leaf to detect the disease.

---

