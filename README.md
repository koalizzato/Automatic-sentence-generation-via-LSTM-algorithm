# Automatic-sentence-generation-via-LSTM-algorithm
This project was my bachelor's thesis project, focused on applying Long Short-Term Memory (LSTM) networks to natural language processing tasks. Specifically, I implemented a deep learning model capable of completing partially started sentences in Italian.

The project consisted of three main phases:

Data Collection and Preprocessing: Over 700 sentences related to chameleons were collected and preprocessed, preserving grammatical correctness to train the model effectively.
Model Design and Training: A bidirectional LSTM architecture was employed with dropout layers to enhance generalization. The model was trained on 250 epochs using an optimized hyperparameter grid.
Sentence Generation: The LSTM model generates sentences by predicting the next word in a sequence, considering prior context. Outputs demonstrate varying quality, influenced by input length and data scarcity.
Despite challenges like limited data and occasional incoherence in multi-word inputs, the model showcases the potential of LSTMs in learning sentence syntax and structure.

This project serves as a foundational exploration of LSTM capabilities in text generation, with insights into their limitations compared to newer Transformer-based models like GPT.
