Plant Disease Detection 🌿

A Flask-based web application that detects plant diseases using a trained Deep Learning model built with MobileNetV2.
Users can upload plant leaf images, and the system predicts the disease category with an easy-to-use web interface.

📌 Features
Upload plant leaf images
Deep Learning disease prediction
User-friendly Flask web interface
Fast and accurate predictions using MobileNetV2
Responsive frontend using HTML & CSS
📂 Project Structure
plant_disease_detection/
│
├── static/
│   ├── images/
│   └── style.css
│
├── templates/
│   ├── about.html
│   ├── home.html
│   ├── result.html
│   └── upload.html
│
├── uploads/
│
├── app.py
├── class_indices (1).json
├── mobilenetv2_final.keras
├── plant_disease_detection.ipynb
└── README.md
🛠️ Technologies Used
Python
Flask
TensorFlow / Keras
MobileNetV2
HTML
CSS
NumPy
PIL (Python Imaging Library)
🚀 Installation
1️⃣ Clone the Repository
git clone https://github.com/dheerajkumar04/plant_disease_detection.git
cd plant_disease_detection
2️⃣ Create Virtual Environment (Optional)
python -m venv venv

Activate virtual environment:

Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
3️⃣ Install Dependencies
pip install flask tensorflow pillow numpy
▶️ Run the Application
python app.py

Open browser and visit:

http://127.0.0.1:5000
📸 How It Works
Upload a plant leaf image
The image is preprocessed
MobileNetV2 model predicts the disease
Result is displayed on the webpage
🧠 Model Information
Model: MobileNetV2
Framework: TensorFlow / Keras
Model File: mobilenetv2_final.keras
📄 Dataset

The model is trained using a plant disease dataset containing different classes of healthy and diseased plant leaves.

📷 Screenshots

Add screenshots of:

Home Page
Upload Page
Prediction Result
👨‍💻 Author

Dheeraj Kumar Gadhe

GitHub: dheerajkumar04
📜 License

This project is developed for educational and learning purposes.
