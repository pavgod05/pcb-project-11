# 🧠 PCB Defect Detection using YOLO

## 📌 Overview
This project focuses on detecting defects in Printed Circuit Boards (PCBs) using deep learning models.  
Multiple YOLO versions (YOLOv5, YOLOv8, YOLO11) were implemented and compared to identify the most effective model.

---

## 🎯 Objective
To automatically detect and classify PCB defects using computer vision and improve accuracy compared to manual inspection.

---

## 📂 Dataset
The dataset consists of PCB images with labeled defects.

### Classes:
- missing_hole
- mouse_bite
- open_circuit
- short
- spur
- spurious_copper

---

## 🛠️ Models Used
- YOLOv5  
- YOLOv8  
- YOLO11  

---

## ⚙️ Methodology
1. Dataset preparation and labeling  
2. Training using YOLO models  
3. Evaluation using performance metrics  
4. Comparison of model outputs  

---

## 📊 Results

| Metric | Value |
|------|------|
| Precision | ~78% |
| Recall | ~62% |
| mAP50 | ~65% |
| mAP50-95 | ~30% |

---

## 📈 Observations
- YOLOv5 produced cleaner predictions but missed some defects  
- YOLOv8 detected more defects but had noise  
- YOLO11 provided the best balance between accuracy and noise  

---

## 🖼️ Sample Output
![Sample Output](images/output.jpg) 

---

## 🧠 Conclusion
YOLO11 achieved the best performance among all models, offering a balance between precision and recall. It is suitable for real-world PCB defect detection.

---

## 🚀 Future Work
- Increase dataset size  
- Improve recall  
- Implement real-time detection system  
- Explore GAN-based data augmentation  

---

## 🧾 Requirements
- Python  
- PyTorch  
- Ultralytics YOLO  

---

## ▶️ How to Run

```bash
pip install ultralytics