# Hierarchical Story Generation Using Neural Networks
Generating stories consisting of multiple paragprahs using a word-RNN model trained on a corpus consisting of several short stories.
The word-rnn model used is a modified version of Tensorflow's char-rnn (https://github.com/sherjilozair/char-rnn-tensorflow).
We trained this on a corpus of text containing all of Sir Arthur Conan Doyle's work for 50 epochs.
The input for the first paragraph must be given, following which the second paragraph uses the last complete sentence of the generated first paragraph.

# Usage:
To train the model:
python train.py
Then change the required prompt in the multipara.py file and run it to generate a multiple paragraph story.
Parameters in the train.py, sample.py and multipara.py files may be changed as per requirements.
