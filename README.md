# Next Word Prediction

![License](https://img.shields.io/badge/license-MIT-green)

## Overview
Next Word Prediction is a machine learning project that predicts the next word in a sentence using a Long Short-Term Memory (LSTM) model. The project is implemented in Python, with model training done in Jupyter Notebooks and the user interface developed using Streamlit.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Streamlit UI](#streamlit-ui)
- [License](#license)
- [Contributing](#contributing)

## Features
- **LSTM Model**: Utilizes LSTM for next word prediction.
- **Interactive UI**: Built with Streamlit for easy interaction.
- **Training Notebooks**: Jupyter Notebooks provided for model training and evaluation.

## Installation
### Prerequisites
- Python 3.8 or higher
- pip
- Libraries - streamlit, tensorflow

## Usage
1. **Training the Model**:
    Open the Jupyter Notebook `train_model.ipynb` and run the cells to train the LSTM model on your dataset.

2. **Running the Streamlit App**:
    After training the model, run the Streamlit app to start the UI:
    ```sh
    streamlit run app.py
    ```

3. **Using the Application**:
    Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`). Enter a sentence and get predictions for the next word.

## Model Training
The model is trained using an LSTM network implemented in Keras. The training process involves:
- Preprocessing the text data
- Tokenizing and creating sequences
- Building and training the LSTM model

Detailed steps are available in the `Next_Word_V2.ipynb` notebook.
After Training a "next_words.h5" File Is Created
Since It A Small Model You Can Pick A Sentence (Minimum Of 3 Words To Be Taken) From `self.txt` And Use That Sentence In UI To Make Predictions

## Streamlit UI
The Streamlit UI (`app.py`) allows users to interact with the model:
- Enter a sentence in the text box
- The app predicts the next word based on the trained LSTM model

![Screenshot 2024-04-08 090327](https://github.com/Vedu-07/Next_Word_Prediction/assets/157512470/2f67724e-3ad5-4f1a-9620-64eed17f67c3)


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements
- [Keras](https://keras.io/)
- [Streamlit](https://www.streamlit.io/)
- [Jupyter](https://jupyter.org/)

## Contact
If you have any questions, feel free to contact me at vedantswami02@gmail.com.

