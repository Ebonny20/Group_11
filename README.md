# Python
fruit and vegetables image classification model

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- Jupyter Lab
- Streamlit
- TensorFlow
- Other required libraries (mentioned in `requirements.txt`)

Install the dependencies:
pip install -r requirements.txt

Launch Jupyter Lab:

Usage
Data Preparation
Dataset Collection: Gather images of various fruits and vegetables into subdirectories (e.g., data/fruits/, data/vegetables/).
Data Processing: Use the provided Jupyter notebooks to preprocess images (resize, normalize, augment).
Dataset Link https://drive.google.com/file/d/1CGiAWso43GCsNo_faRq4jdDIlmwy7YI4/view?usp=sharing

Training and Validation

Open the training notebook:

jupyter lab notebooks/train_model.ipynb
Run the cells to train your model and adjust hyperparameters as needed.
Save the trained model.

Streamlit Application
Start the Streamlit app:
streamlit run app.py
Upload images in the app to get predictions.
