# Helmet Detection (YOLOv8 + ResNet)

This project represents a key milestone in my journey as an aspiring **AI Engineer**.  
As I complete my **AI & Data Science course at SMIT Karachi (taught by Miss Aqsa Moiz)** in December, I am documenting the skills I’ve gained and the projects I’ve built.  

Helmet detection is more than just a technical exercise — it reflects my ability to design, train, and evaluate computer vision models with clarity, reproducibility, and educational impact.

[Live Demo](https://youtu.be/urZsXzjLKEE?si=iN8g_d2-9WRBLaz1)
---


## 🚀 Project Highlights
- **YOLOv8** for helmet vs. no-helmet detection  
- **ResNet** for comparative classification  
- Early stopping & checkpointing integrated into training workflows  
- Clean, modular scripts for reproducibility  
- Visualizations: training curves, confusion matrices, detection samples  

---

## 📂 Structure
```
data/        # datasets (helmet / no-helmet)
notebooks/   # Colab/Kaggle experiments
scripts/     # training & inference scripts
models/      # saved weights & checkpoints
results/     # plots & detection outputs
README.md    # documentation
```

---

## ⚙️ Installation
```bash
git clone https://github.com/<your-username>/helmet-detection-yolov8-resnet.git
cd helmet-detection-yolov8-resnet
pip install -r requirements.txt
```

---

## 🧑‍💻 Usage
### Train YOLOv8
```bash
python scripts/train_yolo.py --epochs 50 --early-stopping
```

### Train ResNet
```bash
python scripts/train_resnet.py --epochs 50 --early-stopping
```

### Run Inference
```bash
python scripts/infer.py --image path/to/image.jpg
```

---

## 📊 Results
- YOLOv8 achieved stronger detection performance compared to ResNet.  
- Visualizations include precision-recall curves, confusion matrices, and detection samples.  

---


## 📈 Business Impact

Helmet detection is not just a technical challenge — it has **real-world safety and compliance implications**:

- **Traffic Safety Enforcement** 🚦  
  City authorities can automatically flag motorcyclists without helmets, reducing accidents and fatalities.  

- **Construction & Industrial Sites** 🏗️  
  Automated monitoring ensures workers follow safety protocols, lowering liability risks and improving workplace compliance.  

- **Insurance & Risk Management** 💼  
  Verified helmet usage data can reduce claims, lower premiums, and strengthen safety audits.  

- **Smart Surveillance Systems** 🎥  
  Integrating helmet detection into CCTV networks enables proactive alerts and real-time monitoring.  

This project demonstrates how AI can move from **academic exercises** to **deployable solutions** that save lives, reduce costs, and improve compliance.

---

## 🔮 Future Work

To extend this project beyond the classroom into **real-world applications**, the following directions are planned:

- **Edge Deployment**  
  Optimize models for devices like Raspberry Pi or Jetson Nano to enable real-time roadside monitoring.  

- **IoT Integration**  
  Connect with CCTV and smart city infrastructure for automated reporting and alerts.  

- **Multi-Class Safety Detection**  
  Expand detection to include seatbelts, reflective jackets, or other PPE for broader compliance monitoring.  

- **Knowledge Distillation**  
  Train lightweight student models for faster inference while maintaining accuracy.  

- **Explainability & Transparency**  
  Add confidence visualization and human-in-the-loop review to build trust in AI decisions.  

---


### Why It Matters
By combining **YOLOv8’s detection accuracy** with **ResNet’s classification capabilities**, this project demonstrates how AI can move beyond academic exercises into **deployable solutions** that save lives, reduce costs, and improve compliance.  

This reflects my transformation from **ML Engineer → Data Scientist → AI Engineer**, showing readiness to tackle projects with **both technical depth and business impact**.

## 🎓 My Learning Journey
This project is part of my **final month at SMIT AI & Data Science**.  
It reflects how far I’ve come — from learning Python and ML basics to building full pipelines with modern frameworks.  
As I step into my career path, I’m preparing to work on **real-world AI projects** with confidence and clarity.  

---
## 🌱 My Transformation

From **ML Engineer** to **Data Scientist**, and now stepping into the role of an **AI Engineer**,  
this project marks the culmination of my learning journey.  

Through my course at **SMIT Karachi (taught by Miss Aqsa Moiz)**, I’ve built skills in Python, data analysis, machine learning, and computer vision.  
This helmet detection pipeline is a milestone that reflects not only technical mastery but also my readiness to contribute to real-world AI projects.

---

## 🙏 Credits
- Instructor: **Miss Aqsa Moiz** (SMIT Karachi)  
- Frameworks: [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics), PyTorch  
- Dataset: Kaggle Helmet Dataset / Open Images Dataset

---
 ## 👩‍💻 Author

*Zahabia Ahmed*  
Data Science Learner | Educator | Content Creator | Aspiring AI Engineer 
[YouTube: Zahabia Ahmed](https://www.youtube.com/@ZahabiaAhmed)
[Instagram](https://www.instagram.com/zahabiaahmed?igsh=MXkwNzkzdGJsMzJqOA==)
[FaceBook](https://www.facebook.com/share/1KBwSz91no/)
[X- Twitter]( https://x.com/AhmedZahabia?t=yAAjSTYTwRRQsXCeomBMuQ&s=08)
[Pinterest](https://pin.it/47OMFKosD)

---

## 📜 License
MIT License – free to use and adapt for educational purposes.
```

---


