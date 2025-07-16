# 📄 Fake Job Postings Detection using DistilBERT & TensorBoard

Detect fake job postings using NLP and visualize training with TensorBoard.

---

## 🚀 Project Overview

This project uses **DistilBERT**, a lightweight transformer model, to classify job postings as real or fake.  
It applies transfer learning on a real-world dataset and visualizes training metrics using **TensorBoard** for easy monitoring.

---

## 📊 Dataset

- **Source:** [Fake Job Postings Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)  
- Includes job titles, descriptions, locations, and a target label indicating whether a posting is fraudulent.

---

## 🛠️ Technologies Used

- **Python**
- **PyTorch**
- **Transformers (Hugging Face)**
- **TensorBoard**
- **Pandas, NumPy**

---

## 📌 Project Structure
```
├── data/ # Raw and preprocessed dataset
├── notebooks/ # Jupyter notebooks for EDA & experiments
├── models/ # Saved model checkpoints
├── tensorboard_logs/ # Logs for TensorBoard visualization
├── main.py # Main training and evaluation script
├── requirements.txt # Project dependencies
└── README.md
```

---

## ✅ Features

- Fine-tunes **DistilBERT** for binary text classification
- Handles text cleaning and tokenization
- Logs loss and accuracy metrics to **TensorBoard**
- Visualizes model performance during training

---

## 📈 Results
Achieved good accuracy on test data.

Visualized training and validation loss, accuracy, and learning curves in TensorBoard for better debugging and tuning.

## 🙌 Acknowledgements
Inspired by various tutorials on transfer learning and NLP fraud detection.

Dataset credits to [Kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction).

## 📬 Contact
Feel free to reach out if you’d like to collaborate or suggest improvements!
- GitHub: Akki-Maharaj
- Linkedin: https://www.linkedin.com/in/akshat--
---
