# Bigram-Language-Model
 Model takes one text file as input, containing a list of words and generates similar words.

 The included names.txt dataset, as an example, has the most common 32K names takes from ssa.gov for the year 2018. The model makes a set of all bigrams from the dataset and creates a frequency distribution.

 A 2D tensor is created, which maps the frequency of occurrence of a letter in the y axis after a letter in the x axis. The tensor is converted into a probability distribution. The probability distribution is used to generate one letter after the other until the end character is generated.

 'Bigram Language Model.ipynb' contains the notebook where the model is created.
 'names.txt. has the input dataset.
 'Generated Names.txt' contains the list of generated names.