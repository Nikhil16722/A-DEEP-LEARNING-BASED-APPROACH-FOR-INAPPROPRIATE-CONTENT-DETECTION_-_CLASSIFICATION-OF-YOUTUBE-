
# 🎥 A Deep Learning-Based Approach for Inappropriate Content Detection and Classification of YouTube Videos

## 📌 Project Overview
The exponential growth of video content on platforms like YouTube has made **content moderation a critical challenge**. This project presents a **deep learning–based automated system** to detect and classify **inappropriate content** such as violence, hate speech, nudity, and misinformation in YouTube videos.

The proposed system analyzes **video frames, metadata, and user interaction signals** to identify harmful content early and accurately, reducing reliance on manual moderation.

---

## 🏫 Academic Details
**Final Year Major Project**  
**Department:** CSE – Data Science  
**Institute:** Swami Vivekananda Institute of Technology  
**Campus:** Mahbub College Campus, Secunderabad  

---

## 🧠 Abstract
Traditional content moderation systems rely on user reports and keyword-based filtering, which are reactive and error-prone. Inappropriate content often appears through **subtle visual, audio, and textual cues**, making it difficult to detect using rule-based methods.

This project leverages **deep learning models** to analyze multimodal data and perform fine-grained classification of YouTube videos. Experimental results show high accuracy and reliability, proving the system’s effectiveness for scalable automated moderation.

---

## 🎯 Objectives
- Detect inappropriate YouTube content automatically  
- Reduce manual moderation delays  
- Analyze multimodal data (video, audio, metadata)  
- Improve accuracy using deep learning models  

---

## 🧠 Technologies Used
- **Programming Language:** Python 3.7  
- **Deep Learning Frameworks:** TensorFlow / PyTorch  
- **Computer Vision:** OpenCV  
- **Libraries:** NumPy, Pandas, Matplotlib  
- **Backend:** Flask / Django  
- **Database:** MySQL  
- **Tools:** Jupyter Notebook, Git, VS Code  

---

## 🏗️ System Architecture
1. Video Input  
2. Frame Extraction  
3. Feature Extraction using CNN  
4. Temporal Learning using LSTM / Attention  
5. Content Classification (Safe / Unsafe)  

### 📸 Architecture Diagram
![System Architecture](screenshots/system_architecture.png)

---

## 🔍 Existing System
- Manual reporting and review  
- Keyword-based filtering  
- Rule-based detection  

### ❌ Disadvantages
- Not scalable  
- High false positives/negatives  
- Cannot detect contextual or hidden violations  
- No real-time detection  

---

## 🚀 Proposed System
The proposed system uses a **deep learning framework with spatial-temporal modeling and attention mechanisms** to detect inappropriate content early.

### ✅ Advantages
- Real-time automated detection  
- Multimodal data analysis  
- Fine-grained classification  
- Scalable for large datasets  
- Reduced human intervention  

---

## 🧩 Modules
### 🔹 Service Provider
- Login  
- Train & test datasets  
- View accuracy graphs  
- Download prediction results  

### 🔹 Admin
- View and authorize users  
- Manage system access  

### 🔹 Remote User
- Register & login  
- Predict YouTube content type  
- View personal profile  

---

## 📂 Project Structure
```text
├── dataset/
├── models/
├── screenshots/
│   ├── system_architecture.png
│   ├── class_diagram.png
│   ├── usecase_diagram.png
│   ├── training_accuracy.png
│   └── prediction_output.png
├── train.py
├── predict.py
├── requirements.txt
└── README.md

📸 Screenshots
🔹 Class Diagram

🔹 Use Case Diagram

🔹 Training Accuracy

🔹 Prediction Output

⚙️ System Requirements
Hardware

1.Processor: Intel i5 / AMD Ryzen 5 or higher
2.RAM: Minimum 8 GB
3.GPU: NVIDIA GPU with CUDA support
4.Storage: 100 GB SSD (recommended)

Software

1.OS: Windows 7 or higher
2.Python 3.7
3.TensorFlow / PyTorch
4.OpenCV, NumPy, Pandas

📈 Results

> High accuracy in detecting unsafe content
> Effective identification of subtle violations
> Suitable for real-world content moderation

🔮 Future Scope

> Multi-class content categorization
> Audio & text (comment) analysis
> Real-time YouTube monitoring
> Web & API deployment


🏁 Conclusion:

This project demonstrates the effectiveness of deep learning-based multimodal analysis for automated YouTube content moderation. By integrating visual, audio, and textual features, the system improves detection accuracy and ensures a safer digital environment, especially for children and teens.

👨‍💻 Author

L. Nikhil
GitHub: https://github.com/Nikhil16722

⭐ If you like this project, give it a star!
