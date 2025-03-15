# NLP Audio Language Detection V6

## Overview
This project focuses on detecting the language of an audio file using NLP techniques and deep learning models. The implementation includes preprocessing audio data, training a classification model, and evaluating its performance.

## Features
- Audio data preprocessing with `librosa`
- Feature extraction using Mel-frequency cepstral coefficients (MFCC)
- Deep learning model built with TensorFlow and Keras
- Hyperparameter tuning with `GridSearchCV`
- Evaluation using classification reports and confusion matrices

## Installation
To set up the project, install the required dependencies:
```sh
pip install numpy pandas librosa tensorflow scikeras tqdm seaborn matplotlib scikit-learn
```

## Usage
Run the notebook step by step to:
1. Import dependencies
2. Load and preprocess audio data
3. Extract features using MFCC
4. Train a deep learning model
5. Evaluate model performance

## Running Commands
### Install Dependencies
Run this command to install all necessary Python packages:
```sh
pip install numpy pandas librosa tensorflow scikeras tqdm seaborn matplotlib scikit-learn
```

### Verify Installation
After installing, you can check if the libraries are properly installed by running:
```sh
python -c "import numpy; import pandas; import librosa; import tensorflow; import sklearn; print('All dependencies installed successfully!')"
```

### Run Jupyter Notebook, Google Colab, or VS Code

#### Jupyter Notebook
If you are using Jupyter Notebook, launch it using:
```sh
jupyter notebook
```
Then, open `My NLP.ipynb` and execute the cells step by step.

#### Google Colab
You can also run the notebook on Google Colab. Upload `My NLP.ipynb` to your Google Drive and open it in Colab.

#### VS Code
If you prefer VS Code, install the Jupyter extension and open the notebook directly in the editor.

## Dependencies
- Python 3.9.4
- TensorFlow
- NumPy
- Pandas
- Librosa
- Matplotlib
- Scikit-learn
- Seaborn
- TQDM
- Scikeras

## Model Architecture
- Sequential Neural Network
- Convolutional layers (Conv2D)
- Pooling layers (MaxPool2D)
- Fully connected layers (Dense)
- Dropout for regularization
- Batch Normalization

## Results
The model's performance is assessed using classification reports and confusion matrices. Adjustments to hyperparameters can be made to optimize accuracy.



