🧠 MRI Brain Tumor Detection Web App
A Flask-based deep learning web app for detecting brain tumors (e.g., Glioma, Pituitary, Meningioma) using MRI scan images.
Built with 💻 TensorFlow, 🔬 Keras, and 🧪 Deep Learning, this application helps identify tumors with high confidence — via a clean and responsive Bootstrap UI that supports light/dark themes.

🚀 Features
✅ Upload any brain MRI image

📊 Predict tumor presence and type: Pituitary, Glioma, Meningioma, or No Tumor

🌗 Toggle between light and dark UI themes

📱 Fully responsive for desktop & mobile

🎨 Clinical-grade UI experience

🔥 Built with Flask + TensorFlow + Bootstrap

## 📸 Screenshots

### 🏠 Home Page
![Home Page](Screenshots/Screenshot%202025-07-02%20130917.png)

---

### 🧠 Tumor Detection Result
![Result Page](Screenshots/Screenshot%202025-07-02%20133233.png)

---  

📽️ Live Demo  
▶️ [Watch Demo Video](https://github.com/Rohit-coder01/Brain_Tumor_Detection_Using_DL/raw/master/demo/demo_video.mp4)



🗂️ Folder Structure
cpp
Copy
Edit
📁 TumorDetectionApp/
├── models/
│   └── model.h5
├── sampleimages/
│   └── test1.jpg, ...
├── uploads/
│   └── (auto-filled)
├── templates/
│   └── index.html
├── main.py
├── requirements.txt
└── README.md
📦 Requirements
Install required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
▶️ Run Locally
bash
Copy
Edit
python main.py


🧠 Model Info
Input image size: 128x128

Model type: CNN (Keras .h5)

Accuracy: 97%~99% (based on your dataset — update as needed)
