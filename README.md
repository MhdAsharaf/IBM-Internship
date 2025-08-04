# ⚡ Power System Fault Detection and Classification using Machine Learning

This project is part of my IBM Internship and focuses on using machine learning to detect and classify faults in electrical power distribution systems. The model is built entirely using **IBM Watson Studio (AutoAI)** without writing any code, and is deployed on **IBM Cloud Lite** for real-time usage.

---

## 🔍 Problem Statement

Power system faults such as Line-to-Ground (LG), Line-to-Line (LL), Double Line-to-Ground (LLG), and Three-phase (LLL) can lead to system instability and blackouts. Traditional methods of fault detection are time-consuming and not efficient for large-scale smart grids. This project aims to automate fault classification using machine learning.

---

## 📊 Dataset Used

- **Source**: [Kaggle - Power System Faults Dataset](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)  
- **Data Type**: Voltage and current phasors recorded under different fault conditions  
- **Format**: CSV file used directly in Watson Studio

---

## 🧠 Project Highlights

- Completely no-code solution using IBM Watson AutoAI  
- Automatic model selection and training  
- Cloud deployment with real-time prediction capabilities  
- Easy-to-understand visual outputs like confusion matrix and accuracy graphs  

---

## 🛠️ Tools & Technologies Used

| Tool/Service | Purpose |
|--------------|---------|
| IBM Watson Studio | ML model training and automation (AutoAI) |
| IBM Cloud Lite | Free-tier hosting for model deployment |
| SPSS Modeler (Optional) | Drag-and-drop ML modeling |
| Kaggle Dataset | Input data for model training |

---

## 🚀 Development & Deployment Steps

1. Uploaded the dataset to IBM Watson Studio.  
2. Used AutoAI to train, test, and evaluate multiple ML models.  
3. Selected the best-performing model (Random Forest).  
4. Deployed the trained model on IBM Cloud as a REST API.

---

## ✅ Results Achieved

- **Best Model**: Random Forest Classifier  
- **Classification Output**:  
  - Fault types: LG, LL, LLG, LLL, and No Fault  
  - Evaluation metrics: Confusion Matrix, Accuracy, Precision  
  - Feature importance visualized for better understanding

---

## 📷 Sample Outputs

Below are sample screenshots from the project:

 ![Inserted Data](screenshots/inserted_data.jpg)
 
 ![Predicted Output](screenshots/predicted_output.jpg)

---

## 📁 Project Directory Structure

```bash
├── data/
│   └── fault_data.csv
├── screenshots/
│   ├── inserted_data.jpg
│   └── predicted_output.jpg
├── Asharaf_IBM_Project.pdf
└── README.md
