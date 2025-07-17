# Heart Disease Prediction System using Machine Learning

![Project Created](https://img.shields.io/badge/June%2019%2C%202025-blue?style=flat-square)  
<br> 
This project is a web-based application that predicts the likelihood of heart disease in a patient based on medical parameters. It uses several machine learning algorithms to train and evaluate predictive models. The application is built using Flask for the backend and features a simple frontend using HTML, CSS, and JavaScript.

---

## Features

- Predicts heart disease based on user input
- Trained using multiple ML algorithms:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors (KNN)
- Trained model saved for fast inference
- Simple UI for input and result display

---

## Tech Stack

- **Languages:** Python, JavaScript, HTML, CSS
- **Framework:** Flask
- **Libraries:** NumPy, Pandas, Matplotlib, scikit-learn
- **Tools:** VS Code, Jupyter Notebook

---

## Installation & Setup

Follow the steps below to set up the project locally:

1. **Install Anaconda** (if not already installed):  
   [Download Anaconda](https://www.anaconda.com/products/distribution)

2. **Clone or download the project folder** and open a terminal in the project directory.

3. **Create a new virtual environment:**

   ```bash
   conda create -n hdp python=3.10

   ```

4. **Activate the environment:**

   ```bash
   conda activate hdp

   ```

5. **Install the required libraries:**

   ```bash
   pip install -r requirements.txt

   ```

6. **Train the model:**

   ```bash
   jupyter notebook
   ```
Open the Heart-Disease-Prediction.ipynb file in your browser

Run all the cells to train the model

A file named models.pkl will be generated in the working directory

7. **Run the Flask application:**

   ```bash
   python app.py

   ```

8. **Open your browser and go to http://localhost:5000 to use the prediction system.**
