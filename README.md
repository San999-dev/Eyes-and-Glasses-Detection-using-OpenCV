# 👀 Eyes and Glasses Detection using OpenCV

## 📌 Overview
This project uses **OpenCV Haar Cascade Classifiers** to detect **eyes and eyeglasses** in real-time through a webcam.  
It highlights detected eyes in **blue** and glasses in **green**, making it easy to distinguish between them.  

---

## ⚙️ Tech Stack
- Python 🐍  
- OpenCV (Haar Cascade Classifiers)  

---

## 🚀 Workflow
1. Load pre-trained Haar cascades (`haarcascade_eye.xml` and `haarcascade_eye_tree_eyeglasses.xml`).  
2. Capture frames from the webcam.  
3. Convert frames to grayscale for better detection.  
4. Detect **eyes** and **glasses** separately.  
5. Draw bounding boxes and labels on detected features.  
6. Display results in real-time until the user presses **'q'**.  

---

## ▶️ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/San999-dev/Eyes-and-Glasses-Detection.git
   cd eyes-glasses-detection

  📊 Output

Blue rectangle → Eye detected 👁️

Green rectangle → Glasses detected 👓

📄 License

This project is licensed under the MIT License.

