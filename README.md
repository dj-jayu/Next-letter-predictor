# Next-letter-predictor
Simple script based on Julian Zucker's Python challenge on the O'Reilly Learning platform.

It predicts the next letter based on training text data using a simple probabilistic choice.

First it downloads the text from publicly available books at https://www.gutenberg.org., saves it to a file, and uses the content to create frequency tables for the prediction.

When running, choose a book by entering one of the following names:

    $ python3 main.py [Frankenstein, Pride and Prejudice, Dracula, and Moby Dick]
