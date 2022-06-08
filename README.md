# NLP_Personality_Classfication
This is my approach to the following project https://github.com/usydnlp/COMP5046NLP_2022.
The input data were first preprocessed and converted into list format. URL was then removed from the data set by using regex. The sentence data then went through a self-built function, which performed number removal, tokenization, stop-words removal and stemming. 
The data were then used to train a word embedding model using a W2V skip-gram algorithm. The self-trained word embedding model was then concatenated with a pre-trained word embedding model (glove-twitter-100)
The model constructed for this project was an n to 1 Bi-LSTM model, meaning that the model takes in n input and product 1 output. The input would be the words in a tweet, and the output would be personality.
