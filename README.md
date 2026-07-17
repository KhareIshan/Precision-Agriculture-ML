# 🌾 Precision Agriculture using Machine Learning

> A web-based machine learning application that recommends suitable crops and predicts crop yield using agricultural datasets through an intuitive Flask interface.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-22C55E?style=for-the-badge)

---

## 📖 Project Overview

Agricultural decision-making depends on several environmental and soil factors. Selecting the most suitable crop and estimating its expected yield can be challenging without reliable data-driven insights.

This project is a Flask-based web application that applies machine learning models trained on agricultural datasets to assist users in two primary tasks:

- 🌱 Recommend suitable crops based on soil and environmental parameters.
- 🌾 Predict crop yield using agricultural input data.

By combining both functionalities into a single platform, the application provides an intuitive interface for generating predictions and demonstrates the practical application of machine learning in precision agriculture.

---

## ✨ Key Features

- 🌱 **Crop Recommendation**
  
Recommends the most suitable crop based on soil nutrients and environmental conditions such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall.

- 🌾 **Crop Yield Prediction**
  
  Predicts crop yield using machine learning models trained on agricultural datasets.

- 🤖 **Machine Learning-Based Predictions**
  
  Generates predictions using trained machine learning models based on user-provided agricultural parameters.

- 🖥️ **Interactive Web Application**
  
  Built with Flask to provide a simple, responsive, and user-friendly interface for making predictions.

- 📊 **Agricultural Dataset Processing**
  
  Utilizes preprocessed agricultural datasets to train and evaluate machine learning models.

- 🔄 **Integrated Prediction Platform**
  
  Combines crop recommendation and crop yield prediction into a single application for a seamless user experience.

---
## 📸 Application Preview

### 🏠 Home Page

<img src="./Screenshots/home.png" alt="Home Page" width="900">

---

### 🌱 Crop Recommendation

**Input Form**

<img src="./Screenshots/crop_prediction_input1.png" alt="Crop Recommendation Input" width="900">

**Additional Input Parameters**

<img src="./Screenshots/crop_prediction_input2.png" alt="Crop Recommendation Additional Inputs" width="900">

**Prediction Result**

<img src="./Screenshots/crop_prediction_result.png" alt="Crop Recommendation Result" width="900">

---

### 🌾 Crop Yield Prediction

**Input Form**

<img src="./Screenshots/yield_prediction_input.png" alt="Yield Prediction Input" width="900">

**Prediction Result**

<img src="./Screenshots/yield_prediction_result.png" alt="Yield Prediction Result" width="900">

---

### 🛎️ Services

<img src="./Screenshots/services.png" alt="Services Page" width="900">

---

## 🛠️ Tech Stack

| Category | Technologies |
| :-------- | :----------- |
| **Programming Language** | Python |
| **Backend Framework** | Flask |
| **Machine Learning** | Scikit-learn |
| **Data Processing** | Pandas, NumPy |
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap |
| **Model Serialization** | Pickle |
| **Development Tools** | Jupyter Notebook, VS Code |
| **Version Control** | Git & GitHub |

---
## 📌 Key Highlights

- ✅ Machine Learning based prediction system
- ✅ Flask web application
- ✅ Crop Recommendation module
- ✅ Crop Yield Prediction module
- ✅ Interactive user interface
- ✅ Agricultural dataset preprocessing
- ✅ Team-based software development
- ✅ Comprehensive technical documentation

---

## 🏗️ System Architecture

```text
                    User
                      │
                      ▼
          Flask Web Application
                      │
         ┌────────────┴────────────┐
         ▼                         ▼
Crop Recommendation        Crop Yield Prediction
         │                         │
         ▼                         ▼
 Machine Learning Models (Scikit-learn)
         │
         ▼
   Prediction Generation
         │
         ▼
 Display Results to User
```

The application accepts user-provided agricultural parameters through a Flask-based web interface. Based on the selected module, the input data is processed by the corresponding machine learning model, and the prediction is displayed to the user in real time.

---
## 📂 Project Structure

```text
precision-agriculture-ml/
│
├── 📄 app.py                    # Main Flask application
├── 📁 crop_recommendation/      # Crop recommendation module
├── 📁 yield_prediction/         # Crop yield prediction module
├── 📁 data/                     # Datasets used for training and prediction
├── 📁 docs/                     # Project documentation and report
├── 📁 graphs/                   # Graphs and visualizations
├── 📁 screenshots/              # Images used in the README
├── 📁 static/                   # CSS, JavaScript, and static assets
├── 📁 templates/                # HTML templates
├── 📄 README.md                 # Project documentation
```
---

### 🔗 Quick Navigation

| Resource | Description |
| :--- | :--- |
| [`app.py`](./app.py) | Main Flask application |
| [`crop_recommendation/`](./crop_recommendation) | Crop recommendation module |
| [`yield_prediction/`](./yield_prediction) | Crop yield prediction module |
| [`data/`](./data) | Agricultural datasets |
| [`docs/`](./docs) | Project report and documentation |
| [`graphs/`](./graphs) | Graphs and visualizations |
| [`templates/`](./templates) | HTML templates |
| [`static/`](./static) | Static assets (CSS, JavaScript, Images) |
| [`screenshots/`](./screenshots) | Application screenshots |

---
## 🎯 Project Objectives

The primary objectives of this project are:

- Develop a web-based application for precision agriculture.
- Recommend suitable crops using machine learning techniques.
- Predict crop yield based on agricultural parameters.
- Demonstrate the practical application of machine learning in agriculture.
- Provide an intuitive interface for interacting with predictive models.

---

## ⚙️ Installation

Follow these steps to set up the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/KhareIshan/precision-agriculture-ml.git
```

### 2. Navigate to the project directory

```bash
cd precision-agriculture-ml
```

### 3. Create and activate a virtual environment (Recommended)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install the required Python packages

Install the project dependencies manually or using a `requirements.txt` file (recommended for future updates).

---

## 🚀 Running the Application

After completing the installation, start the Flask development server:

```bash
python app.py
```

Once the server is running, open your web browser and navigate to:

```text
http://127.0.0.1:5000/
```

You can now access the application and use the following modules:

- 🌱 Crop Recommendation
- 🌾 Crop Yield Prediction

The application accepts agricultural input parameters through the web interface and generates predictions using the trained machine learning models.

---

## 🧠 Machine Learning Workflow

The application follows a structured machine learning pipeline to generate predictions from user-provided agricultural data.

```text
                Agricultural Dataset
                        │
                        ▼
               Data Preprocessing
                        │
                        ▼
            Machine Learning Model Training
                        │
                        ▼
               Trained Model (.pkl)
                        │
                        ▼
        User Inputs Through Flask Interface
                        │
                        ▼
              Input Data Preprocessing
                        │
                        ▼
              Prediction Generation
                        │
                        ▼
           Recommendation / Yield Result
```

### Workflow Overview

1. Agricultural datasets are collected and preprocessed.
2. Machine learning models are trained using the processed datasets.
3. Trained models are saved for future predictions.
4. Users provide agricultural parameters through the Flask web interface.
5. The application preprocesses the input data and passes it to the trained model.
6. The model generates a prediction, which is displayed to the user through the web application.

---
## 🔮 Future Improvements

The following enhancements can further improve the functionality, accuracy, and usability of the application:

- 🌦️ Integrate real-time weather APIs, IoT sensors, and satellite imagery for dynamic crop recommendations based on live soil, weather, and environmental conditions.
- 🦠 Add pest and disease prediction modules with preventive recommendations using weather patterns and historical agricultural data.
- 🌱 Provide personalized fertilizer and irrigation recommendations tailored to specific crop and soil conditions.
- 📱 Develop a mobile application and ☁️ deploy the system on cloud platforms to improve accessibility, scalability, and public availability.
- 📈 Enhance prediction accuracy by incorporating larger, more diverse datasets collected from agricultural agencies, research institutions, and government sources.
- 🤖 Continuously improve the machine learning pipeline by experimenting with advanced ML and deep learning models.
- 🌍 Expand support for multiple crops, regions, farming practices, and regional languages to make the system more inclusive and practical.

---
## 👥 Team & My Contribution

This project was developed as part of a **5-member university team**.

### My Contribution

My primary responsibilities included:

- 🤖 Assisted in training and evaluating machine learning models.
- 📚 Conducted technical research and literature review related to precision agriculture and machine learning.
- 📄 Prepared the complete project documentation and technical report.
- 📝 Contributed to the research paper preparation and documentation.
- 🤝 Collaborated with team members during project integration, testing, and final deployment.

Working on this project strengthened my understanding of Flask, machine learning workflows, collaborative software development, and technical documentation.

---
## 🙏 Acknowledgements

This project was developed as part of a university academic project.

The application was built by studying existing machine learning implementations, understanding their architecture, and extending them by integrating crop recommendation and crop yield prediction into a unified Flask-based application. The project was further customized, updated, and adapted to meet the academic objectives and improve compatibility with modern Python libraries.

Special thanks to our faculty mentors and team members for their guidance and collaboration throughout the project.

---
## 📚 References

The project was developed using concepts from machine learning, Flask development, and agricultural datasets. Helpful resources include:

- Scikit-learn Documentation
- Flask Documentation
- Pandas Documentation
- NumPy Documentation

---
## 📜 License

This repository is shared for educational and learning purposes.

If you use this project for academic work or further development, appropriate credit to the original contributors is appreciated.

---
