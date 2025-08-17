# Human Activity Recognition (HAR) using Sensor Fusion  

## Overview  
This project implements **Human Activity Recognition (HAR)** using time-series data from wearable motion sensors (accelerometer & gyroscope). By combining two benchmark datasets — **UCI HAR** and **PAMAP2** — we designed robust deep learning models to classify human activities such as walking, sitting, standing, and lying down.  

The work explores **sensor fusion**, advanced preprocessing techniques, and hybrid neural architectures (**CNN, LSTM, Bi-LSTM, CNN-LSTM with Attention**) to improve recognition accuracy across multiple sensor setups.  

---

##  Key Features  
-  **Sensor Fusion**: Combined accelerometer and gyroscope signals along 3 axes (X, Y, Z).  
-  **Preprocessing**: Resampling (K-Max Pooling), normalization, segmentation (2.56s windows, 50% overlap), and label alignment.  
-  **Deep Learning Models**: Implemented 1D-CNN, LSTM, Bi-LSTM, and hybrid CNN-LSTM with Attention.  
-  **Performance**: Achieved ~91% accuracy and 90.8% F1-score across six core activities.  
-  **Applications**: Smart healthcare (fall detection, elderly monitoring), fitness tracking, IoT automation, firefighting/military safety monitoring.


<img width="337" height="120" alt="Screenshot 2025-08-15 at 11 29 58 AM" src="https://github.com/user-attachments/assets/fb1757e5-5b76-49a9-a77d-6f26e5e15858" />

<img width="462" height="153" alt="Screenshot 2025-08-15 at 11 29 53 AM" src="https://github.com/user-attachments/assets/8ad3ac5b-854c-4cce-ac3a-c16a84acf7b0" />



---

##  Results  
| Dataset        | Model       | Accuracy | F1-Score |
|----------------|------------|----------|----------|
| UCI HAR       | 1D-CNN     | 94.16%   | 94.21    |
| PAMAP2 (Hand) | 1D-CNN     | 92.08%   | 92.18    |
| UCI + PAMAP2  | CNN-LSTM   | 90.58%   | 88.82    |

- **Validation Accuracy:** 90.84%  
- **Validation F1-Score:** 90.82% (macro weighted)


<img width="467" height="336" alt="Screenshot 2025-08-15 at 11 29 41 AM" src="https://github.com/user-attachments/assets/aaaaab0d-fd74-4448-9d69-3b133b98ec1d" />


---

## 📂 Datasets  
- **[UCI HAR Dataset](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones)**  
- **[PAMAP2 Dataset](https://archive.ics.uci.edu/dataset/231/pamap2+physical+activity+monitoring)**  

---

##  Tech Stack  
- **Python**, **NumPy**, **Pandas**, **Matplotlib**  
- **TensorFlow / Keras**  
- **Scikit-learn**  
- **Jupyter Notebook**  

---

##  Applications  
-  Wearables: Smartwatches, fitness trackers, mobile health apps  
-  Healthcare: Fall detection, elderly care, rehabilitation monitoring  
-  Fitness: Activity recognition and workout tracking  
-  IoT: Smart homes with movement-based automation  
-  Military & Firefighting: Real-time activity monitoring for safety  

---

##  Author  
**Sajandeep Singh**  
- 🌐 [LinkedIn](www.linkedin.com/in/sajandeep9812)  
- 📧 work.sajandeep@gmail.com  

---

