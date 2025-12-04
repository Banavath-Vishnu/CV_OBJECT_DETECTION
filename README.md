cat << 'EOF' > README.md
# 🧠 Object Detection with YOLOv3 using Google Colab  

## 👥 Team – Group 3  
- **Banavath Vishnu**  
- **Uday Sukaraboin**  
- **Vadthya Ram Charan**

---

## 📌 Project Overview  
This project performs **object detection** using the **YOLOv3 model** executed fully on **Google Colab**.  
YOLOv3 identifies objects in images and videos and draws bounding boxes with class labels and confidence scores.

---

## 🚀 Key Features  
- Runs entirely on **Google Colab** (no local setup)  
- Detects 80+ object categories (COCO dataset)  
- Supports **images and videos** as input  
- Uses pretrained **YOLOv3** weights  
- Visualizes detections with bounding boxes and labels  

---

## 🧰 Tools & Technologies  

| Tool / Library | Purpose                         |
|----------------|---------------------------------|
| Google Colab   | Cloud execution (CPU / GPU)     |
| Python         | Core programming language       |
| OpenCV         | Object detection & visualization|
| NumPy          | Numerical operations            |
| Matplotlib     | Displaying results              |

---

## ▶ How to Run on Google Colab  

### 1️⃣ Open the Notebook  
Upload or open the notebook: **\`CV_OBJECT_DETECTION.ipynb\`** in Google Colab.

---

### 2️⃣ Install Dependencies (in Colab)

```bash
!pip install opencv-python matplotlib numpy
