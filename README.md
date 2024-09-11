Text Processing and N-gram Creation: The code reads a text file (demo.txt), tokenizes the text into words using word_tokenize, and generates bigrams (2-word sequences) with the ngrams function. It stores these bigrams in a Pandas DataFrame with two columns: "first_word" and "second_word."

Next Word Prediction: After the user enters a word, the program searches the DataFrame for matching entries where the input word is the "first_word" and predicts up to two possible "second_word" values, printing them as suggestions.

Data Handling: If no prediction is found (word not in the dataset), the code prompts the user to add new data. It appends the entered word to the demo.txt file for future use, expanding the dataset.
