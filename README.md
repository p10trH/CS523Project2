# MadLibs-RNN
Generate answers to MadLibs-ish styled templates using a RNN/LSTM

Mostly reused code from https://github.com/hunkim/word-rnn-tensorflow by Sung Kim

...which is mostly reused code from https://github.com/sherjilozair/char-rnn-tensorflow which was inspired from Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn).

# Requirements
- [Tensorflow](http://www.tensorflow.org)

# Basic Usage
To train with default parameters on the tinyshakespeare corpus, run:
```bash
python3 train.py
```

To start the GUI and sample from a trained model. (Store madlib templates in "data/")
```bash
python3 ui_madlibs.py
```

# Sample Output
see Proj2/sample output/

# Demo
https://youtu.be/czaY-vQi0ac
