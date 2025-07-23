# Assignment 2 - Encoder Decoder using LSTM

 I have implemented an encoder-decoder model using LSTM for English to French translation. I used a toy dataset (5 sentence pairs) for training.


## What I have done

- I created a small dataset with English and French sentence pairs
- Used Tokenizer to convert words into sequences and padded them
- Built an encoder and decoder using LSTM (Keras)
- Trained the model for 10 epochs and printed loss after each
- Did translation using greedy search for 5 test sentences
- Also plotted training loss graph
  

## Tools and Libraries Used

- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab


## How to run this

1. Open the `.ipynb` file in Google Colab or Jupyter
2. Run all cells one by one
3. You’ll see training loss printed after each epoch
4. At the end, 5 English sentences will be translated into French


## Output
Input: hi → Predicted: salut
Input: how are you → Predicted: comment ça va
Input: i am fine → Predicted: vais bien
Input: thank you → Predicted: merci
Input: good morning → Predicted: bonjour





