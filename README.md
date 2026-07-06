# Capstone-Project-Neural-Networks

# 🧠 Business Slogan Generator and Industry Classifier Using Neural Networks

## Overview

This project was completed as part of the **HyperionDev Data Science Bootcamp** and demonstrates the application of **deep learning** and **Natural Language Processing (NLP)** to solve two related business problems.

Using a dataset of business slogans and their corresponding industries, the project develops two Long Short-Term Memory (LSTM) neural network models:

* A **Slogan Generator** that creates new business slogans based on a selected industry.
* An **Industry Classifier** that predicts the industry of a business from its slogan.

The project combines text preprocessing, sequence modelling, and neural network training to showcase practical applications of deep learning in NLP.

---

## Project Objectives

The project focuses on building an end-to-end NLP solution that can:

* Preprocess text data
* Tokenise and encode business slogans
* Train an LSTM-based slogan generation model
* Train an LSTM-based industry classification model
* Evaluate model performance
* Generate new slogans
* Predict industries from generated slogans
* Compare generated outputs with classifier predictions

---

## Dataset

The project uses a dataset containing:

* Business Names
* Business Slogans
* Industry Categories

The dataset provides examples from multiple industries, enabling both text generation and classification tasks.

---

## Technologies Used

* Python 3
* Jupyter Notebook
* TensorFlow / Keras
* NumPy
* Pandas
* Scikit-learn
* spaCy
* Matplotlib

---

## Project Structure

```text
Neural-Network-Slogan-Generator/
│
├── neural_network_task.ipynb      # Main notebook
├── slogans_dataset.csv            # Dataset
├── README.md                      # Project documentation
└── images/                        # Optional screenshots and model outputs
```

---

## Data Preprocessing

The text data was prepared by:

* Loading the dataset
* Removing missing values
* Extracting relevant columns
* Cleaning text
* Tokenising slogans
* Encoding industry labels
* Padding sequences
* Preparing training and testing datasets

Proper preprocessing ensures the models receive consistent numerical input suitable for deep learning.

---

## Slogan Generator

An LSTM neural network was developed to generate business slogans based on a selected industry.

The generator:

* Accepts an industry as input
* Learns language patterns from existing slogans
* Produces new slogan suggestions
* Demonstrates sequence generation using recurrent neural networks

---

## Industry Classifier

A second LSTM model was trained to classify business slogans into their corresponding industries.

The classifier:

* Uses tokenised slogan sequences
* Predicts the most likely industry
* Evaluates performance on unseen data
* Demonstrates supervised text classification

---

## Model Evaluation

The project evaluates both models by:

* Measuring classification accuracy
* Testing slogan generation quality
* Comparing generated slogans with classifier predictions
* Analysing similarities and differences between expected and predicted industries

This combined workflow demonstrates how text generation and classification can complement one another.

---

## Skills Demonstrated

* Natural Language Processing (NLP)
* Deep Learning
* Neural Networks
* Long Short-Term Memory (LSTM)
* Text Tokenisation
* Text Encoding
* Sequence Modelling
* Text Classification
* Text Generation
* Model Evaluation
* Python Programming

---

## Learning Outcomes

Through this project I gained practical experience in:

* Preparing text data for deep learning
* Building LSTM neural networks
* Working with sequential data
* Generating text using neural networks
* Performing text classification
* Evaluating NLP models
* Applying machine learning concepts to real-world business data

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/neural-network-slogan-generator.git
```

Navigate to the project directory:

```bash
cd neural-network-slogan-generator
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
neural_network_task.ipynb
```

Run all notebook cells to reproduce the preprocessing, model training, evaluation, and slogan generation.

---

## Future Improvements

Potential enhancements include:

* Using pre-trained word embeddings such as Word2Vec or GloVe
* Fine-tuning transformer models such as BERT or GPT
* Improving slogan diversity through advanced text generation techniques
* Hyperparameter optimisation
* Deploying the models as a web application using Streamlit or Flask
* Supporting multilingual slogan generation
* Expanding the dataset with additional industries

---

## Project Deliverables

* ✔️ Data preprocessing and tokenisation
* ✔️ LSTM-based slogan generator
* ✔️ LSTM-based industry classifier
* ✔️ Model evaluation
* ✔️ Generated business slogans
* ✔️ Industry prediction for generated slogans
* ✔️ Well-documented Jupyter Notebook

---

## Author

Developed as part of the **HyperionDev Data Science Bootcamp** to demonstrate practical applications of **Neural Networks**, **Natural Language Processing (NLP)**, and **Deep Learning**.

---

## License

This project is intended for educational and portfolio purposes.
