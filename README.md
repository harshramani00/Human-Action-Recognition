# Swift-Spatio Flow: A Human Action Recognition Model Using 3D CNN-LSTM

## 📌 Project Overview

**Swift-Spatio Flow** is an advanced **Human Action Recognition (HAR)** model that combines **3D Convolutional Neural Networks (3D CNN)** with **Long Short-Term Memory (LSTM)** networks. This project aims to improve action recognition in videos by efficiently extracting **spatial and temporal features** while reducing computational cost.

🚀 **Key Applications**
- CCTV surveillance enhancement
- Assisting the visually impaired
- Self-driving cars
- Sports analytics

## 🎯 Problem Statement
Existing HAR models suffer from:
- **Complexity:** High computational cost
- **Accuracy:** Difficulty in handling low-quality videos
- **Scalability:** Struggle with large datasets

**Swift-Spatio Flow** addresses these challenges by integrating a **3D CNN and LSTM** to extract spatial and temporal features efficiently.

## 📊 Methodology
1. **Preprocessing:** 
   - Extract frames from videos
   - Resize and normalize images
   - Convert frames into sequences

2. **Model Architecture:** 
   - 3D CNN for feature extraction
   - LSTM for sequence modeling
   - Softmax activation for classification

3. **Training & Evaluation:**
   - Dataset: **UCF-50**
   - Metrics: **Accuracy, Precision, Recall, F1-score**
   - Comparison with existing models

## 🏆 Results
| Model                 | Accuracy (%) | Precision (%) | Recall (%) | F1 Score (%) |
|----------------------|-------------|-------------|-----------|-------------|
| CNN + LSTM          | 76.12       | 75.94       | 74.17     | 75.86       |
| ConvLSTM2D         | 78.95       | 78.74       | 76.14     | 78.68       |
| Time Distributed CNN | 88.50       | 88.00       | 87.52     | 87.71       |
| 3D CNN (UCF-101)    | 91.65       | 89.96       | 90.82     | 91.10       |
| **Swift-Spatio Flow** | **94.89**  | **94.37**  | **93.45** | **93.56** |

🔮 Future Enhancements
Train on larger datasets like Kinetics for better generalization
Optimize computational cost for real-time performance
Deploy the model as a web application


🤝 Contributors

- Ian Joseph K
- Aryan Patil (https://github.com/aryanator)
- Abhishek Raje
- Ramani Harsh Anilkumar
