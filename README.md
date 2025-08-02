# Smart Weather Monitoring - CNN Project

## Project Overview
This project implements a **Convolutional Neural Network (CNN)** for classifying weather conditions from images.  
It includes the full machine learning pipeline:  
- Data preprocessing  
- Data augmentation  
- Model training with hyperparameter tuning  
- Performance evaluation and error analysis  

The final model achieves high classification accuracy and demonstrates the applicability of deep learning for **weather pattern recognition** in real-world applications.

---

## Dataset Download Instructions
We use the **Multi-class Weather Dataset** from Kaggle.

**Steps to Download:**
1. Go to the dataset page: [https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset)  
2. Click **Download** (You may need to log in to Kaggle).  
3. Unzip the downloaded file.  
4. Place the unzipped dataset directory **in the root directory of this project** (same level as the notebook file).

After extraction, the dataset folder structure should look like this:
```text
project_root/
│
├── weather-monitoring-CNN.ipynb
└── Multi-class Weather Dataset/
    ├── Cloudy/
    ├── Rain/
    ├── Shine/
    └── Sunrise/
```
---

## How to Run the Code

To reproduce the results presented in the final report, follow these steps:

1. **Install dependencies**  
   Make sure you have Python 3.8+ installed, then run:
   ```bash
   pip install tensorflow keras numpy pandas matplotlib scikit-learn
   ```
2.	**Open the notebook** jupyter notebook weather-monitoring-CNN.ipynb
3. **Execute all cells**  
   In the Jupyter interface, select **Kernel → Restart & Run All** to:
   - Preprocess the dataset  
   - Train the CNN model  
   - Evaluate performance on validation and test sets  
   - Generate evaluation metrics and plots (confusion matrix, accuracy curves, etc.)

---

### Expected Output
- Training logs showing accuracy & loss progression  
- Test accuracy near **95.31%**  
- Confusion matrix for test-set performance  
- Sample predictions highlighting correct/incorrect classifications  

---

### Requirements
- Python 3.8+  
- TensorFlow 2.x  
- Keras  
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn  
- Jupyter Notebook  

---

### Author  
Group 8 – Jingjing Zhai, Zhiruo Zhang, Yuchen Ma  
SEP 769 – Cyber Physical Systems  
Faculty of Engineering, McMaster University  
Hamilton, ON, Canada  