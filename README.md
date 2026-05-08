Iris-Flower-Classification-Using-Streamlit
A machine learning classification web application that predicts the species of an Iris flower based on sepal and petal measurements. The application uses a Random Forest Classifier trained on the famous Iris dataset and provides real-time predictions through an interactive Streamlit interface.
Dataset
The project uses the Iris Flower dataset.
Dataset file used:
Iris.csv
Main columns:


sepal_length


sepal_width


petal_length


petal_width


class


Target variable:
class
Input features:


sepal_length


sepal_width


petal_length


petal_width


Output classes:


Iris-setosa


Iris-versicolor


Iris-virginica



Algorithms Used
The following machine learning classification algorithm was used:


Random Forest Classifier


Best Algorithm
The best-performing model used:
Random Forest Classifier
The trained model is saved as:
rf_model.sav

Evaluation Metric
The model was evaluated using:


Accuracy Score


Example accuracy:
Accuracy: 0.91

Tech Stack
Machine Learning


Python


Pandas


NumPy


Scikit-learn


Joblib


Web Framework


Streamlit


Version Control


Git


GitHub



Project Structure
Iris-Flower-Classification/│├── Data/│   └── Iris.csv│├── app.py├── model.py├── prediction.py├── rf_model.sav├── requirements.txt└── README.md

How to Run Locally
Clone the repository:
git clone https://github.com/YOUR_USERNAME/Iris-Flower-Classification.git
Move into the project folder:
cd Iris-Flower-Classification
Create a virtual environment:
python -m venv venv
Activate virtual environment on Windows:
venv\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Train the model:
python model.py
Run the Streamlit application:
streamlit run app.py
Open in browser:
http://localhost:8501

Requirements
streamlitpandasnumpyscikit-learnjoblib
