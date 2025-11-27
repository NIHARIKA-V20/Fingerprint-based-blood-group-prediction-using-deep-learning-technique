Title: Fingerprint-Based Blood Group Prediction Using Deep Learning Technique

This project is a web-based application that predicts a person’s blood group using their fingerprint image. It uses a deep learning model trained on fingerprint patterns and provides results through a Flask-based web interface.

Project Features:
Upload a fingerprint image and get the predicted blood group
Deep learning model using TensorFlow and Keras
User login and signup pages
Clean HTML UI design
Fully functional Flask web application
Deep Learning Model Used

The application uses a trained model:
baseline_model.keras

The model is loaded in app.py for predictions.

Project Folder Structure:
Fingerprint-based-blood-group-prediction-using-deep-learning-technique
├── static/
│ ├── finger.jpg
│ ├── finger1.jpg
│ └── new2.jpg
│
├── templates/
│ ├── index.html
│ ├── login.html
│ ├── signup.html
│ └── prediction.html
│
├── app.py
├── baseline_model.keras
├── requirement.txt
└── README.md

Installation and Setup:
1. Clone the Repository
git clone your repository link
cd Fingerprint-based-blood-group-prediction-using-deep-learning-technique

2. Create a Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate (Windows)

3. Install Required Packages
pip install -r requirement.txt

Dependencies (from requirement.txt):
tensorflow==2.18.0
keras==3.7.0
numpy==2.0.2
pillow==11.0.0
Flask==3.1.0
Flask-SQLAlchemy==3.1.1
SQLAlchemy==2.0.36

Run the Application
Run the main app:
python app.py

Visit in browser:
http://127.0.0.1:5000/

Upload a fingerprint image → get predicted blood group.

Home Page – uses images like:
static/finger.jpg
Prediction Page – uses images like:
static/new2.jpg

Future Enhancements:
Improve fingerprint preprocessing
Train with advanced models (ResNet, MobileNet)
Deploy online (Render/Heroku)
Add user history and database features

Author:
Niharika V
Deep Learning & Web Development Enthusiast

License

This project is for academic and research purposes only.
