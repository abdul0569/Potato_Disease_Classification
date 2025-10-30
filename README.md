# 🥔 Potato Disease Classification using Deep Learning

This project is a **Potato Leaf Disease Classification System** built using **Deep Learning (TensorFlow/Keras)** for image classification, with a **Flask API** backend and a **React.js frontend**.

The model predicts whether a potato leaf is:
- 🟢 **Healthy**
- 🟠 **Early Blight**
- 🔴 **Late Blight**

---

## 🚀 Project Architecture
<img width="1124" height="319" alt="image" src="https://github.com/user-attachments/assets/2c855eba-cdca-47fc-8526-356d5627f63d" />


## 📁 Project Structure
```
E:.
│ models.config
│ Potato_Disease_Classification.ipynb # Jupyter notebook for model training
│
├───api # Backend (Flask API)
│ main-tf-serving.py
│ main.py
│ Procfile
│ requirements.txt
│ runtime.txt
│
├───frontend # Frontend (React.js)
│ │ .env.example
│ │ package.json
│ │ README.md
│ ├───public
│ │ index.html
│ └───src
│ App.js
│ home.js
│ index.js
│ bg.png
│ leaf.jpg
│ cblogo.PNG
│
└───saved_models # Trained TensorFlow models (versions)
├───1
├───2
└───3
```

## 🚀 Features

- 🧠 Deep Learning model trained with TensorFlow/Keras  
- 🧾 Flask API for serving model predictions  
- 🌐 React frontend for uploading and classifying potato leaf images  
- 🧰 Model versioning (saved_models/1, 2, 3)  
- ☁️ Ready for deployment (supports Heroku or Render)  

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/<your-username>/potato-disease-classification.git
cd potato-disease-classification
```

**🔧 Setup Instructions**
  ```
  cd api

  python -m venv venv
  source venv/bin/activate   # On Windows: venv\Scripts\activate
  ```
- Install Dependencies
```
pip install -r requirements.txt
```
- Run the API
```
python main.py
```

**💻 Frontend — React.js**
- Navigate to the frontend folder:
```
cd frontend
```
- Install dependencies:
```
npm install
```
- Start the development server:
```
npm start
```

