# text-onehot-tokenization
a system to onehot encode text from a dictionary


create an encoder_words.txt file with your vocabulary seperated by \n like so:

apple\n
banana\n
fruit\n
etc...\n


run the function with the text you want to tokenize and you will get a 1D tensor from the text
the tensor size is the following:

how many words are in the vocabulary * how many words were encoded
