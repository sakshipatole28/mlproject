# 🎓 Student Performance Prediction – End-to-End Machine Learning Project

This project is an **end-to-end Machine Learning web application** that predicts student exam performance based on various demographic and academic attributes. The application includes the full ML lifecycle — from **data preprocessing and model training to deployment on the cloud**.

The model predicts a student's **math score** using input features such as gender, parental education level, lunch type, and other academic indicators.

The application is deployed using **AWS Elastic Beanstalk**, making it accessible through a live web interface.

---

# 🚀 Live Application

The project is deployed on the cloud and can be accessed here:

**Live Demo:**
`http://performanceanalysis-ml-env.eba-iwpamris.ap-southeast-2.elasticbeanstalk.com/`

Users can enter student information in the form and receive a predicted math score instantly.

---

# 📌 Project Overview

Educational institutions often want to analyze the factors affecting student performance. This project uses machine learning to predict student outcomes based on various attributes.

The application allows users to input student details and uses a trained ML model to predict the expected **math exam score**.

### Input Features

The model uses the following features:

* Gender
* Race / Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

### Target Variable

* **Math Score**

---

# 🧠 Machine Learning Pipeline

The project follows a modular ML pipeline architecture:

1. **Data Ingestion**
   Reads raw dataset and splits it into training and testing data.

2. **Data Transformation**
   Performs feature engineering and preprocessing.

3. **Model Training**
   Multiple machine learning models are trained and evaluated.

4. **Model Evaluation**
   Models are compared using evaluation metrics to select the best performer.

5. **Prediction Pipeline**
   The trained model is loaded and used to generate predictions for new input data.

---

# ⚙️ Technologies Used

### Programming Language

* Python

### Machine Learning Libraries

* Scikit-learn
* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Web Framework

* Flask

### Cloud & Deployment

* AWS Elastic Beanstalk
* AWS CodePipeline

### Development Tools

* Visual Studio Code
* GitHub

---

# 🧪 Machine Learning Models Used

The following regression models were trained and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor
* CatBoost Regressor

The best-performing model was selected based on evaluation metrics and saved for deployment.

---

# 🌐 Web Application

The web interface is built using **Flask**.

### Application Features

* Interactive user interface
* Input form for student attributes
* Real-time prediction results
* Deployed on cloud infrastructure

### Routes

```
/              → Home page
/predictdata   → Student input form
```

Users enter student data in the form and the model returns the predicted math score.

---

# ☁️ Cloud Deployment

The application is deployed using **AWS Elastic Beanstalk**, which manages the infrastructure automatically.

### Deployment Architecture

```
GitHub Repository
        │
        ▼
AWS CodePipeline
        │
        ▼
Elastic Beanstalk Environment
        │
        ▼
Flask Web Application
```

This setup allows automatic build and deployment of the application.

---

# 🖥️ Local Installation & Setup

### Clone the Repository

```
git clone https://github.com/<your-username>/student-performance-ml-project.git
cd student-performance-ml-project
```

### Create Virtual Environment

```
python -m venv venv
```

### Activate Environment

Windows

```
venv\Scripts\activate
```

Mac / Linux

```
source venv/bin/activate
```

### Install Dependencies

```
pip install -r requirements.txt
```

### Run the Application

```
python application.py
```

### Open in Browser

```
http://localhost:5000
```

---

# 📊 Dataset

The dataset contains student academic and demographic information used to analyze performance.

Typical columns include:

* gender
* race_ethnicity
* parental_level_of_education
* lunch
* test_preparation_course
* reading_score
* writing_score
* math_score

The goal is to predict **math_score** based on other attributes.

---

# 📈 Future Improvements

Possible future enhancements for the project include:

* Docker containerization
* Model monitoring and logging
* REST API implementation using FastAPI
* Database integration for storing predictions
* Automated CI/CD workflows
* Model retraining pipeline

---

# 👩‍💻 Author

**Sakshi Patole**

Machine Learning Enthusiast and Software Developer

GitHub Profile:
[https://github.com/sakshipatole28](https://github.com/sakshipatole28)

---

# ⭐ Support

If you found this project useful or interesting, consider giving it a **star ⭐ on GitHub**.
