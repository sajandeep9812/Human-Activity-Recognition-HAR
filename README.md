# Human Activity Recognition (HAR) using Sensor Fusion  
##  Research Paper
Read the full report here: [Human Activity Detection Paper (PDF)](https://drive.google.com/file/d/1fRXHi0hpfc6uKKnCijgORsrq9BZRQ7lx/view)


## Overview  
This project implements **Human Activity Recognition (HAR)** using time-series data from wearable motion sensors (accelerometer & gyroscope). By combining two benchmark datasets — **UCI HAR** and **PAMAP2** — we designed robust deep learning models to classify human activities such as walking, sitting, standing, and lying down.  

The work explores **sensor fusion**, advanced preprocessing techniques, and hybrid neural architectures (**CNN, LSTM, Bi-LSTM, CNN-LSTM with Attention**) to improve recognition accuracy across multiple sensor setups.  

---

##  Key Features  
-  **Sensor Fusion**: Combined accelerometer and gyroscope signals along 3 axes (X, Y, Z).  
-  **Preprocessing**: Resampling (K-Max Pooling), normalization, segmentation (2.56s windows, 50% overlap), and label alignment.  
-  **Deep Learning Models**: Implemented 1D-CNN, LSTM, Bi-LSTM, and hybrid CNN-LSTM with Attention.  
-  **Performance**: Achieved ~91% accuracy and ~89% F1-score across six core activities.  
-  **Applications**: Smart healthcare (fall detection, elderly monitoring), fitness tracking, IoT automation, firefighting/military safety monitoring.
<p align="center">
  <img src="https://github.com/user-attachments/assets/fb1757e5-5b76-49a9-a77d-6f26e5e15858" alt="Raw Data" width="600"/>
  <img src="https://github.com/user-attachments/assets/8ad3ac5b-854c-4cce-ac3a-c16a84acf7b0" alt="Time Window Segmentation" width="700"/>
</p>




---

##  Results  
| Dataset        | Model       | Accuracy | F1-Score |
|----------------|------------|----------|----------|
| UCI HAR       | 1D-CNN     | 94.16%   | 94.21    |
| PAMAP2 (Hand) | 1D-CNN     | 92.08%   | 92.18    |
| UCI + PAMAP2  | CNN-LSTM   | 90.58%   | 88.82    |

<p align="center">
  <img src="https://github.com/user-attachments/assets/aaaaab0d-fd74-4448-9d69-3b133b98ec1d" alt="HAR Preprocessing Visualization" width="700"/>
</p>



---

## 📂 Datasets  
- **[UCI HAR Dataset](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones)**  
- **[PAMAP2 Dataset](https://archive.ics.uci.edu/dataset/231/pamap2+physical+activity+monitoring)**  

---

##  Tech Stack  
- **Python**, **NumPy**, **Pandas**, **Matplotlib**  
- **TensorFlow / Keras**  
- **Scikit-learn**  
- **Google Colab**  

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

