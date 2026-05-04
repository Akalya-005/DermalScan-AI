🧴 DermalScan AI – Intelligent Skin Analysis System

An AI-powered skin analysis web application developed during the Infosys Springboard Internship, designed to detect skin conditions, analyze facial features, and provide insights using deep learning and computer vision techniques.

🚀 Project Overview

DermalScan AI is an end-to-end intelligent system that analyzes facial images to:

Detect skin conditions
Estimate age-related features
Provide visual and analytical outputs

The system integrates Deep Learning (CNN) and Computer Vision techniques to deliver accurate and real-time predictions.

It is built as a full-stack application with a user-friendly frontend and a powerful backend inference engine.

➡️ Similar systems use CNN models and image-processing pipelines to classify dermatological conditions effectively

✨ Key Features
📸 Image upload with real-time preview
🧠 AI-based skin condition detection
👤 Face detection (single & multiple faces)
🎯 Age estimation using deep learning
🧩 Multi-face handling using Non-Maximum Suppression (NMS)
🖼️ Annotated output visualization
📊 Prediction summary & performance tracking
📁 Export results (CSV + images)
🌐 Clean and responsive UI
🏗️ System Architecture
User Input Image
        ↓
Face Detection (OpenCV / DNN)
        ↓
Preprocessing (Resize, Normalize)
        ↓
Deep Learning Model (CNN)
        ↓
Prediction (Skin Condition + Age)
        ↓
Visualization & Output (UI + Export)
🧠 Technologies Used
🔹 Frontend
HTML, CSS, JavaScript
React.js / Vite (if used in your repo)
🔹 Backend
Python
Flask
🔹 AI / ML
TensorFlow / Keras
OpenCV
CNN (Convolutional Neural Networks)
🔹 Tools
Git & GitHub
VS Code / PyCharm
Jupyter Notebook
📂 Project Structure
DermalScan-AI/
│
├── client/                # Frontend (React / UI)
├── server/                # Backend (Flask APIs)
├── model/                 # Trained ML models
├── dataset/               # Training dataset
├── static/                # Images / assets
├── templates/             # HTML templates
├── app.py                 # Main backend file
├── requirements.txt       # Dependencies
└── README.md              # Documentation
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Akalya-005/DermalScan-AI.git
cd DermalScan-AI
2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app.py
5️⃣ Open in Browser
http://127.0.0.1:5000/
🧪 How It Works
User uploads an image
System detects face(s) using OpenCV
Image is preprocessed (resize, normalize)
CNN model analyzes features
Outputs:
Skin condition classification
Age estimation
Results are displayed with annotations
📊 Model Details
Model Type: Convolutional Neural Network (CNN)
Task: Image Classification + Feature Extraction
Training:
Image preprocessing & augmentation
Optimization using Adam / SGD
Output:
Class probabilities
Confidence score
📈 Performance Metrics
Accuracy
Precision
Recall
F1 Score

(You can update with your actual values if needed)

💡 Use Cases
🏥 Early skin condition detection
💄 Skincare analysis & recommendations
📱 Health-tech mobile/web apps
🧪 Research in dermatology AI
⚠️ Limitations
Not a replacement for medical diagnosis
Accuracy depends on dataset quality
Sensitive to lighting and image clarity
Limited to trained skin condition classes
🔮 Future Enhancements
🔍 More disease categories
📊 Explainable AI (Grad-CAM visualization)
📱 Mobile application version
☁️ Cloud deployment (AWS / Azure)
🤖 Integration with chatbot for consultation
🤝 Contribution

Contributions are welcome!

Steps:

Fork the repo
Create a new branch
Commit your changes
Submit a Pull Request
📜 License

This project is licensed under the MIT License.

🙌 Acknowledgements
Infosys Springboard Internship Program
Open-source ML & Computer Vision communities
Public dermatology datasets
👩‍💻 Author

Akalya K

AI & ML Enthusiast|  AIDS Student
Linkedin: https://www.linkedin.com/in/akalya-k-548937294?utm_source=share_via&utm_content=profile&utm_medium=member_android

⭐ Final Note
“AI in healthcare is not just innovation — it’s impact.”
