# Hierarchical Story Generation Using Neural Networks
Generating stories consisting of multiple paragprahs using a LSTM trained on a corpus consisting of several short stories.

The word-rnn model used is a modified version of Tensorflow's char-rnn (https://github.com/sherjilozair/char-rnn-tensorflow).

We trained this on a corpus of text containing all of Sir Arthur Conan Doyle's work for 100 epochs.

The input for the first paragraph must be given, following which the second paragraph uses the last complete sentence of the generated first paragraph. The story is made to follow a pre-selected theme based on customizable sentiment tokens for each paragraph.

The model is deployed via Flask.

# Sample output:

Prompt: As he walked into the street he was afraid of what might happen to him.

Theme: Mystery

Output:

As he walked into the street he was afraid of what might happen to him. That was our own danger? But I think that I broke it down upon my breast. I could only saw my hair and a sharp chuckle in the room which he is, however, unpaid, so because he might break his house, but he was an old doctor, but I know with them at the beginning of the French Museum down with seven thousand wolves all the use of insects, an quarry. A night chirrup or word, you would be glad to put up up. And what do you hesitate?" "There is only local subjects coming from the woods," said he.

There are decidedly parties at the moment this morning--a cheerful, a connoisseur as Captain William began to conclude nothing of our worthy of humours, and I observed that my horror was afar. "By my soul! they have not encouraged me ill?" I kept my girth to the house and to eat and let me be welcome to both," said he. Inscribed round in a brisker chair, and slamming his plate from the table beside him. He was dressed than that mind shown that a luckless evening, and in no muscle of anger had been lopped off from them.


# Usage:
To train the model:

python train.py

Then change the required prompt in the multipara.py file and run it to generate a multiple paragraph story.

Parameters in the train.py, sample.py and multipara.py files may be changed as per requirements.

