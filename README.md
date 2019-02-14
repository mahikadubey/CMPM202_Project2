# CMPM202_Project2
Word RNN and Image Autoencoder

## Word RNN
For part 1, I compiled my own personal diary entries from 2007 to 2009, and generated some results using a word-based RNN. The results were interesting, generating some sentences that made partial sense. Given the small dataset size, the paragraphs were not always comprehensible. 

# Basic Usage
Adapted from https://github.com/hunkim/word-rnn-tensorflow

To train
```bash
python train.py data/[folder_with_input.txt]
```

To sample from a trained model
```bash
python sample.py
```

## Autoencoder
