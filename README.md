# NLP-A8
NLP assignments from AIT

**Kaung Htet Cho (st124092)**

# Task-1
## Dataset

The [Alpaca Dataset](https://github.com/instruction-data-collection/alpaca-data) was used for training the language model. The dataset was downloaded and mapped to a JSON format using the `dataset` package.

# Task-2
## Model Training

The language model was trained using the SFT (Supervised Fine-Tuning) approach with the `Trainer` class from the Hugging Face Transformers library. The Alpaca dataset was incorporated into the existing code framework for training.

# Task-3
## Model Evaluation

The trained model was evaluated using the Alpaca evaluation dataset. 

# Task-3
## Web Application

A simple web application was developed using Flask to demonstrate the capabilities of the trained language model. The application includes the following features:

1. An input box where users can enter a text prompt.
2. Based on the user input, the model generates and displays a continuation of the text.
3. The web application interfaces with the trained language model through the Flask backend through localhost:8000
