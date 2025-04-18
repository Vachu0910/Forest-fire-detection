---

## 🔥 UAV-Based Forest Fire Monitoring and Prediction System

This project focuses on the development of machine learning models for real-time forest fire detection and predictive analysis, integrated into a UAV-based (Unmanned Aerial Vehicle) surveillance system. The system leverages computer vision and time-series prediction to enhance the efficiency and accuracy of forest fire management.

---

### 🚀 Features

- **YOLOv5-based Fire Detection Model**  
  Utilizes a custom-trained YOLOv5 model on RGB and thermal imagery for high-accuracy, real-time fire detection with reduced false positives.

- **Fire Spread Prediction using RNNs**  
  Implements a Recurrent Neural Network (RNN) to forecast the progression of forest fires based on environmental and historical data, achieving over 90% prediction accuracy.

- **LiDAR-Enhanced Terrain Awareness**  
  Incorporates LiDAR data for topographical mapping to help the predictive model account for terrain influence on fire spread.

- **Edge-Deployable Architecture**  
  Optimized for real-time processing on UAV onboard systems with GPU support.

---

### 🧠 Machine Learning Models

- **Object Detection:** YOLOv5 (CNN-based)
- **Prediction:** RNN for time-series fire spread forecasting
- **Training Framework:** PyTorch
- **Evaluation Metrics:** mAP, IoU, Accuracy, Loss

---

### 🛠️ Tech Stack

**Python | YOLOv5 | PyTorch | RNN | CNN | LiDAR | Thermal Imaging | RGB Imaging | mAP | IoU | Data Augmentation**

---

### 📊 Dataset

- Custom dataset of forest fire imagery (thermal + RGB)
- Annotated for fire detection using bounding boxes
- Historical fire and environmental data for training RNN

---

### 📈 Results

- 🔍 **Detection Accuracy:** Significant reduction (30%) in false positives
- 🔮 **Prediction Accuracy:** 92% accuracy in fire spread forecasting
- ⚡ **Real-Time Inference:** Models optimized for UAV onboard hardware

---

### 📌 Future Work

- Enhance model robustness in extreme weather conditions
- Expand dataset diversity for better generalization
- Explore transformer-based time-series models for prediction

---

