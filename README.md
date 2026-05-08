# Iris-Flower-Classification-Using-Streamlit

A machine learning classification web application that predicts the species of an Iris flower based on sepal and petal measurements. The application uses a Random Forest Classifier trained on the famous Iris dataset and provides real-time predictions through an interactive Streamlit interface.

## Dataset

The project uses the Iris Flower dataset.

Dataset file used:

Iris.csv

Main columns:

- sepal_length
- sepal_width
- petal_length
- petal_width
- class

### Target Variable

class

### Input Features

- sepal_length
- sepal_width
- petal_length
- petal_width

### Output Classes

- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

# Algorithms Used

The following machine learning classification algorithm was used:

- Random Forest Classifier

## Best Algorithm

Best-performing model:

- Random Forest Classifier

Saved model file:

rf_model.sav

---

# Evaluation Metric

The model was evaluated using:

- Accuracy Score

Example accuracy:

Accuracy: 0.91

---

# Tech Stack

## Machine Learning

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Web Framework

- Streamlit

## Version Control

- Git
- GitHub

---

# Project Structure

```text
Iris-Flower-Classification/
│
├── Data/
│   └── Iris.csv
│
├── app.py
├── model.py
├── prediction.py
├── rf_model.sav
├── requirements.txt
└── README.md
# How to Run Locally

## Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Iris-Flower-Classification.git
```

## Move into the project folder

```bash
cd Iris-Flower-Classification
```

## Create virtual environment

```bash
python -m venv venv
```

## Activate virtual environment (Windows)

```bash
venv\Scripts\activate
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Train the model

```bash
python model.py
```

## Run the Streamlit app

```bash
streamlit run app.py
```
## Open in browser

```text
https://irisprediction-gv2viwk48shrynarztmjrl.streamlit.app/
```
