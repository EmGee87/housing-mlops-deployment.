# Housing Price Predictor - MLOps Deployment

This repository demonstrates a basic MLOps deployment workflow for predicting housing prices using a trained linear regression model and a Gradio web interface.

##Repository Contents

- `Housing.csv`: Dataset used to train the model.
- `train.py`: Script to train and save the model as `model.pkl`.
- `model.pkl`: Pre-trained linear regression model.
- `app.py`: Gradio-based web interface to input house details and get a predicted price.
- `requirements.txt`: Python package dependencies for the project.

## 🚀 How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/housing-mlops-deployment.git
cd housing-mlops-deployment

## 2. Install Required Packages
Make sure you have Python installed, then run:

bash
Copy
Edit
pip install -r requirements.txt
3. Launch the Web App
bash
Copy
Edit
python app.py
This will open a Gradio web interface where you can enter the area, number of bedrooms, and bathrooms to get an estimated house price.
