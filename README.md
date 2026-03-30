# 🧠 Brain Tumor Detection using Deep Learning & Graph-Based Learning

## 📌 Overview

This project focuses on detecting brain tumors from MRI images using a hybrid deep learning approach that combines **3D Convolutional Neural Networks (CNNs)** with **graph-based feature learning**.

The pipeline includes preprocessing of volumetric MRI scans, patch extraction, graph construction using superpixels, and tumor classification using a deep neural network model.

## 🚀 Key Features

* 📊 MRI image preprocessing and normalization
* 🧩 Patch-based learning for 3D volumetric data
* 🔗 Graph construction using SLIC superpixel segmentation
* 🧠 Deep learning model (3D U-Net inspired architecture)
* 📈 Evaluation using classification metrics (Accuracy, F1-score, etc.)
* ⚡ Efficient handling of high-dimensional medical data

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Deep Learning:** PyTorch
* **Numerical Computing:** NumPy
* **Machine Learning Metrics:** Scikit-learn
* **Visualization:** Matplotlib

## 📂 Project Structure

Brain-Tumor-Detection/
│
├── notebook.ipynb        # Main implementation
├── README.md             # Project documentation
├── requirements.txt      # Dependencies

## 🧪 Methodology

### 1. Data Preprocessing

* MRI scans are normalized and cropped
* Patch extraction is applied to handle large 3D volumes

### 2. Graph Construction

* Superpixel segmentation (SLIC) is used
* Each region is treated as a node
* Adjacency matrix represents relationships between regions

### 3. Model Architecture

* Custom **3D U-Net inspired CNN**
* Feature extraction from volumetric patches
* Integrated with graph-based representation

### 4. Training & Evaluation

* Model trained on multiple patient samples
* Evaluated using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * ROC-AUC

## 📊 Results

* Achieved strong performance in tumor classification
* Demonstrated effective feature learning using graph-based approach
* Stable training with consistent loss reduction

*(Exact training pipeline and model weights are not publicly shared.)*

## ⚠️ Important Note

* Dataset is not included due to size and licensing restrictions
* Training and evaluation pipeline have been partially hidden to protect intellectual property

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Open the notebook and execute step-by-step


## 👨‍💻 Author

**Shubham Singh**

---

## 📬 Contact

For full implementation, dataset access, or collaboration opportunities, feel free to connect.
