# Neural network from Scratch using NumPy

- To understand the working of Neural networks - To build a neural network from scratch using NumPy

## Overview
A neural network is a set of algorithms that aim to recognize the underlying pattern in the data. These are subsets of Machine learning and the heart of deep learning algorithms. Neural networks are inspired by the working of the human brain. Neural networks are applied in many real-life applications like self-driving cars, speech recognition, medical diagnosis, and many more. In this project, we will be building a neural network from scratch just by using NumPy only and not by using any deep learning frameworks like Tensorflow or PyTorch. The built neural network will predict the price of the house in Pune, India. This project will also give you an in-depth idea about the working of neural networks.

## Data
The dataset contains information about the prices of houses based on various attributes. The dataset contains the prices of houses from Pune, Maharashtra(India).

_Data is not included in this repository._

## Approach
- Data Preprocessing ○ Removing null values ○ Scaling numerical features ○ One-Hot encoding of categorical data
- Model Training ○ Training neural network model
- Model Evaluation ○ Evaluation of model on test data

Modular Code Overview:

Once you unzip the neural_network.zip file, you can find the following folders within it.
1. Input
2. ML_Pipeline
3. Notebook
4. Resources
5. Engine.py
6. Readme.md
7. requirements.txt
1. The Input folder contains the data that we have for analysis. In our case, it contains the house price prediction dataset
2. The Notebook folder contains the jupyter notebook file of the project
3. The ML_pipeline is a folder that contains all the functions put into different python files, which are appropriately named. These python functions are then called inside the Engine.py file
4. The Resources folder contains the materials used in the project
5. The requirements.txt file has all the required libraries with respective versions. Kindly install the file by using the command pip install -r requirements.txt
6. All the instructions for running the code are present in Readme.md file

## Tech stack
➔ Language: Python ➔ Libraries: pandas, sci-kit learn, numpy

## How to run
```bash
pip install -r neural_network/requirements.txt
```
Notebooks: [`04_nn_demo.ipynb`](neural_network/Notebook/04_nn_demo.ipynb), [`01_real_world.ipynb`](neural_network/Resources/01_real_world.ipynb), [`02_history.ipynb`](neural_network/Resources/02_history.ipynb), [`03_neural_net.ipynb`](neural_network/Resources/03_neural_net.ipynb)

## Project structure
```
.gitignore
Notebook.zip
README.md
Solution Methodology.pdf
data.zip
neural_network.zip
neural_network/
  Engine.py
  ML_Pipeline/
    Neural_Network.py
    Preprocessing.py
  Notebook/
    04_nn_demo.ipynb
  READ ME.md
  Resources/
    01_real_world.ipynb
    02_history.ipynb
    03_neural_net.ipynb
  requirements.txt
```

## Credits
Based on a ProjectPro guided project.
