# Next Word Prediction Using LSTM

This project aims to develop a deep learning model for predicting the next word in a given sequence of words. The model is built using Long Short-Term Memory (LSTM) networks with Tensorflow and Keras, which are well-suited for sequence prediction tasks.

## Streamlit Deployment

The application is deployed using Streamlit. You can access it without running the code locally by visiting the following link:

[Streamlit App](https://next-word-prediction-lstm-ztw4a4hu54tnpgn7943pmx.streamlit.app/)

## Setup (if you want to run locally)

1. Clone the repository:
    ```sh
    git clone https://github.com/OnurAsimIlhan/next-word-prediction-lstm.git
    cd next-word-precition-lstm
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. To run the main application locally:
    ```sh
    streamlit run app.py
    ```

2. To explore the experiments and model training, open `experiments.ipynb` in Jupyter Notebook:
    ```sh
    jupyter notebook experiments.ipynb
    ```
