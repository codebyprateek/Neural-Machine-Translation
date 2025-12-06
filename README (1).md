# Neural Machine Translation (NMT)

## 📌 Project Overview

This project implements a **Neural Machine Translation (NMT)** system
capable of translating text from **French to English** using a
sequence‑to‑sequence (Seq2Seq) model with **LSTM-based encoder and
decoder** networks.

The goal of this project is to demonstrate how deep learning can be
applied to machine translation using the fundamental architecture behind
many modern translation systems.

------------------------------------------------------------------------

## 🚀 Features

-   Text preprocessing: tokenization, cleaning, and padding\
-   Encoder--Decoder architecture\
-   LSTM-based sequence modelling\
-   Teacher forcing during training\
-   Trained on a bilingual French--English dataset\
-   Ability to translate unseen French sentences into English

------------------------------------------------------------------------

## 🧠 Model Architecture

### **1. Encoder**

-   Processes French input sequences\
-   Converts them into a context vector (final hidden state)

### **2. Decoder**

-   Takes the context vector\
-   Generates English translation word-by-word\
-   Uses LSTMs and dense layers with softmax activation

------------------------------------------------------------------------

## 📂 Dataset

The project uses a bilingual dataset (**French--English sentence
pairs**) extracted from the uploaded `fra-eng.zip`.

------------------------------------------------------------------------

## 🛠 Technologies Used

-   Python\
-   TensorFlow / Keras\
-   NumPy\
-   Pandas\
-   NLP preprocessing utilities

------------------------------------------------------------------------

## 📘 How to Run

``` bash
pip install tensorflow numpy pandas
```

Open the notebook:

``` bash
Neural Machine Translation.ipynb
```

Run all the cells to preprocess the data, train the model, and perform
translations.

------------------------------------------------------------------------

## 📈 Results

The trained model is capable of generating basic English translations.
Performance improves with: - Larger datasets\
- More epochs\
- Attention mechanisms (future improvement)

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Add **Attention Mechanism (Bahdanau / Luong)**\
-   Use **GRU** or **Transformer-based** models\
-   Train on larger datasets\
-   Deploy as an API using Flask or FastAPI

------------------------------------------------------------------------

## 🙌 Acknowledgments

This project was completed as part of a Machine Learning internship
task.

------------------------------------------------------------------------

## 👤 Author

**Prateek**
