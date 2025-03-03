# 🎥 HUMAN-MOTION-PREDICTION-USING-CNN

This project presents an **Action Recognition System** using a **3D Convolutional Neural Network (3D CNN)** built with **Keras** and **OpenCV** to classify human actions from video clips. The model is designed to recognize five actions: **Boxing, HandWaving, Jogging, Running,** and **Walking**. 

The repository includes:
- **Sample Input Videos:** A collection of videos for testing the model.
- **`code.ipynb`:** Jupyter notebook containing the complete code for data preprocessing, model training, and prediction.
- **`documentation.pdf`:** Detailed documentation explaining the project architecture, implementation, and results.
- **`liveCamera.ipynb`:** Source code for implementing live camera feed to the model. 
- **Pretrained Model Weights:** For easy testing and inference.

Additionally, the model can take input from both **pre-recorded videos** and a **live camera feed** to predict actions in real-time.

---

## 📌 Introduction

This project aims to classify human actions using a 3D CNN, leveraging both spatial and temporal features from video sequences. It is designed for applications such as **surveillance systems, sports analytics,** and **gesture recognition**.

To demonstrate the model’s capabilities, a few **sample input videos** have been included in the repository. Additionally, the model can be updated to real-time input from a **live camera** and predict actions instantly.

---

## 🛠 Key Modules and Libraries

**1. Deep Learning Framework:**
- `Keras` and `TensorFlow` - For building and training the 3D CNN model.

**2. Video Processing:**
- `OpenCV` - For reading and preprocessing video frames.

**3. Data Handling:**
- `NumPy` and `Pandas` - For handling data arrays and CSV files.

**4. Machine Learning Utilities:**
- `scikit-learn` - For splitting datasets and model evaluation.

**5. Visualization:**
- `Matplotlib` - For plotting results and performance metrics.

**Key Libraries Installation:**

```bash
pip install keras tensorflow opencv-python numpy pandas scikit-learn matplotlib
