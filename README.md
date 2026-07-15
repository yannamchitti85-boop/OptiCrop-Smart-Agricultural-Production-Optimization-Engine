🌾 OptiCrop – Smart Agricultural Production Optimization Engine

An AI-powered Agricultural Recommendation System that uses Machine Learning to optimize crop production based on soil and environmental parameters. The application provides intelligent crop recommendations through a simple Flask web interface, helping farmers maximize yield and resource efficiency.



 📌 Project Overview

Agriculture is the backbone of many economies, but optimizing crop production remains a challenge due to varying soil and climate conditions. Timely and data-driven crop selection enables farmers to improve yield, reduce costs, and promote sustainable farming.

This project uses historical soil and environmental data to train multiple machine learning models and recommend the most suitable crop to grow. The best-performing model is integrated into a Flask web application, allowing users to enter parameters like NPK, temperature, humidity, pH, and rainfall to instantly receive a crop recommendation.

The OptiCrop engine helps farmers, researchers, agribusiness companies, and policymakers make evidence-based decisions for better productivity, sustainability, and resource utilization.



🎯 Objectives

- Predict the most suitable crop using machine learning.
- Improve agricultural productivity and resource efficiency.
- Provide a simple and user-friendly recommendation interface.
- Compare multiple machine learning algorithms and select the best-performing model.
- Support sustainable and data-driven farming practices.
- Enable future deployment on cloud platforms.



 ✨ Features

- Soil and environmental data analysis
- Data preprocessing and feature engineering
- Multiple machine learning models
    - K-Nearest Neighbors (KNN)
    - Logistic Regression
    - Decision Tree
    - Random Forest
    - K-Means Clustering
- Model evaluation and comparison
- Best model selection and serialization with Pickle
- Flask-based web application
- Interactive crop recommendation dashboard
- Instant Crop Recommendation based on input parameters



 🛠️ Technology Stack

Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript

 Backend
- Python 3.10+
- Flask

 Machine Learning
- Scikit-learn
- SciPy
- Seaborn

 Libraries
- Pandas
- NumPy
- Matplotlib
- Pickle
- Jupyter Notebook



 📁 Project Structure

```
OptiCrop/
├── app.py
├── requirements.txt
├── README.md
├── dataset/
├── model/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   └── result.html
└── notebooks/
```



⚙️ Installation

**Clone the repository:**
```bash
git clone https://github.com/yannamchitti85-boop/OptiCrop-Smart-Agricultural-Production-Optimization-Engine
```

**Move into the project directory:**
```bash
cd OptiCrop
```

**Install the required dependencies:**
```bash
pip install -r requirements.txt
```

**Run the Flask application:**
```bash
python app.py
```

**Open your browser and visit:**
```
http://127.0.0.1:5000
```



 💻 How to Use

1. Open the application.
2. Navigate to the recommendation page.
3. Enter soil and environmental parameters: N, P, K, Temperature, Humidity, pH, Rainfall.
4. Click Get Recommendation.
5. View the recommended crop for maximum yield.



📊 Machine Learning Workflow

1. Dataset Collection
2. Data Preprocessing
3. Feature Engineering
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Best Model Selection
8. Model Saving with Pickle
9. Flask Deployment
10. User Recommendation



🧠 Models Used

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Random Forest
- K-Means Clustering

The models were trained and evaluated on historical agricultural data containing soil nutrients and environmental parameters. The best-performing model was selected and integrated into the Flask application for crop recommendation.



🚀 Future Enhancements

- Cloud Deployment: AWS / Azure / IBM Cloud
- Real-time Weather API Integration
- User Authentication and Profile
- Crop Prediction History
- Interactive Data Visualization Dashboard
- SMS and Email Farming Alerts
- Geographic Crop Suitability Mapping
- Integration with IoT soil sensors



 👥 Team Members
 
 1. Nidhrabingi Kavitha - Team lead
 2. Anusuri Asha Deepa - Member
 3.  Keerthana Adam - Member
 4.  Siva Nagendra Egaia - Member
 5.  Birada Jaswanth - Member



🖥️ System Requirements

 Hardware Requirements
- Processor: Intel Core i3 or above
- RAM: Minimum 4 GB
- Storage: Minimum 10 GB free space
- Internet Connection for downloading datasets and packages

Software Requirements
- Operating System: Windows / Linux / macOS
- Python 3.x
- Anaconda Navigator
- Jupyter Notebook / Spyder
- Visual Studio Code or PyCharm
- Flask Framework



 📄 License

This project is developed for educational and academic purposes.



 ⭐ Acknowledgement

We thank our mentors, faculty members, teammates, and the providers of the agricultural dataset and open-source libraries that made this project possible.




Demo Video

🎥 Demo Video:
https://drive.google.com/file/d/1F9WYG1dns7xFmOMZ-50XUHKvrgeIrSrB/view?usp=drivesdk





