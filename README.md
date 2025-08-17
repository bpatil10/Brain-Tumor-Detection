**Brain Tumour Detection using CNN
Overview**

This project focuses on detecting brain tumours from MRI scans using deep learning techniques. A Convolutional Neural Network (CNN) was trained to classify MRI images into Tumour and Non-Tumour categories. The goal was to assist in early diagnosis, reduce manual effort, and provide a reliable automated approach for medical image analysis.

**Tech Stack**
**Programming Language:** Python
**Libraries/Frameworks**: TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn
**Tools:** Jupyter Notebook, Google Colab

**Repository Structure**
├── brain_tumor_detection.ipynb   # Jupyter Notebook (exploration + visualizations)
├── brain_tumor_detection.py      # Python script (clean runnable code)
├── dataset/                      # MRI dataset (not included, link below)
├── README.md                     # Project documentation

**Dataset**
The dataset contains MRI brain images categorised into Tumour and Non-Tumour.
Dataset Link: Brain MRI Images Dataset (Kaggle)

**Implementation Steps**
Preprocessed MRI images (resizing, normalisation).
Built a CNN model with convolutional, pooling, and dense layers.
Trained and validated the model on the dataset.
Evaluated performance using accuracy, precision, recall, and a confusion matrix.

**Results**
Achieved 98.9%% accuracy on test data.
The CNN model successfully classified MRI scans into Tumour/Non-Tumour classes.
Visualisation of training performance is included in the notebook.

**Output**
<img width="691" height="400" alt="image" src="https://github.com/user-attachments/assets/361e6af9-1913-43a5-8944-fd61459e9d88" />


**How to Run**

**Clone the repo:**

git clone https://github.com/yourusername/brain-tumor-detection.git
cd brain-tumor-detection

**Run with Jupyter Notebook:**
jupyter notebook brain_tumor_detection.ipynb

**Or run directly with Python:**
python brain_tumor_detection.py

**Future Improvements**
Experiment with transfer learning using pre-trained models (ResNet, VGG16).
Optimise hyperparameters for higher accuracy.
Extend to multi-class tumour type classification.

**Acknowledgements**
**Dataset**: Kaggle Brain MRI Images
**Frameworks**: TensorFlow & Keras

Dataset: Kaggle Brain MRI Images

Frameworks: TensorFlow & Keras
