# Cat and Dog Classifier using Deep Learning

This project develops a Deep Learning model to perform binary image classification, distinguishing between images of cats and dogs. The classification system is built using the **PyTorch** framework and is trained on the large-scale Microsoft Cats vs. Dogs dataset.

## 📌 Features

  * **Binary Image Classification:** Classifies images into 'Cat' or 'Dog'.
  * **Deep Learning Model:** Implemented with the PyTorch framework.
  * **Image Preprocessing & Augmentation:** Includes data transformations (resizing, normalization, augmentation) for robust training.
  * **Complete Training Pipeline:** Covers model loading, training loop, and validation within a single notebook.
  * **Performance Evaluation:** Metrics include Accuracy, and a visual Confusion Matrix (indicated by the plotting parameters in the notebook).

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **Python** | Core programming language |
| **PyTorch** | Deep Learning framework (Version 2.6.0+ is noted in the notebook) |
| **Torchvision** | Image dataset, model, and transformation utilities for PyTorch |
| **Pandas, NumPy** | Data handling and numerical operations |
| **Matplotlib, Seaborn** | Visualization (loss curves, confusion matrix, etc.) |
| **Jupyter Notebook** | Development environment for the workflow |

## 📂 Project Structure

```
├── cat-and-dog-classifier.ipynb  # Main notebook with the DL workflow
├── README.md                     # Project documentation (this file)
```

## 📊 Dataset

The model is trained on the **Microsoft Cats vs. Dogs Dataset**.

  * **Source:** The data paths in the notebook reference `/kaggle/input/microsoft-catsvsdogs-dataset/`.
  * **Content:** Contains thousands of image files categorized into two classes:
      * `Cat`
      * `Dog`

## 🚀 How to Run

### 1\. Clone the Repository

```bash
git clone https://github.com/yourusername/cat-and-dog-classifier.git
cd cat-and-dog-classifier
```

### 2\. Install Dependencies

Install PyTorch and other required libraries. The core environment should support PyTorch (version 2.6.0+ is mentioned).

```bash
# Recommended minimum installation
pip install torch torchvision torchaudio numpy matplotlib
```

### 3\. Setup Dataset

Ensure the Microsoft Cats vs. Dogs Dataset is downloaded and organized in a directory structure accessible to the notebook (e.g., inside a `data/` folder).

### 4\. Run Jupyter Notebook

Execute the notebook to run the full pipeline, including data loading, model training, and evaluation.

```bash
jupyter notebook cat-and-dog-classifier.ipynb
```

## 📈 Results

The notebook provides comprehensive metrics to evaluate the model's performance on the validation and test sets.

  * **Metrics Tracked:** Training Accuracy, Validation Accuracy, and Testing Accuracy.
  * **Validation Accuracy:** **\~98.37%**
  * **Test Accuracy:** **\~99%** (which shows that no overfitting)
  * **Visualizations:** A Confusion Matrix is used to inspect the model's predictive performance for each class.
  * ***Note:*** *Specific accuracy results will depend on the hardware, training time, and specific architecture used in the notebook.*


---

## 👨‍💻 Author

Developed by **Haroon Waheed**

---
