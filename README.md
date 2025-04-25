# Handwritten Digit Recognition

A Streamlit-based web application that recognizes handwritten digits using a Convolutional Neural Network (CNN) trained on the MNIST dataset.

## 📁 Project Structure

```yaml
Handwritten-Digit-Recognition/
├── App.py                  # Main Streamlit app
├── requirements.txt        # List of required Python packages
├── model/
│   ├── Main_Model.ipynb    # Jupyter Notebook for model training
│   ├── mnist_model.h5      # Saved Keras model
│   └── handwritten.h5      # Additional model (if used)
├── prediction/
│   └── digit.png           # Sample image for prediction
├── venv/                   # Virtual environment (DO NOT PUSH TO GITHUB)
```
---
## 🚀 How to Run the Project

```yaml
Steps:
  - clone the repository
  - navigate to the project directory
  - create a virtual environment (optional but recommended)
  - activate the virtual environment
  - install dependencies from requirements.txt
  - run the Streamlit app

Commands:
  - git clone https://github.com/HimanshuSadhwani/Handwritten-Digit-Recognition.git
  - cd Handwritten-Digit-Recognition
  - python -m venv venv
  - venv\Scripts\activate        # On Windows
  - pip install -r requirements.txt
  - streamlit run App.py
```
