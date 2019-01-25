# Text-Classification-using-GloVe-and-LSTM (NLP)
Natural Language Processing
## From data preparation to building model and deploy the model to web service.

### [Part 1 : Preparing data](https://github.com/Sweetflowerjulia/NLP-Model_Text-Category-with-GloVe-and-LSTM/blob/master/Preparing%20data.ipynb)
 - read document
 - clean data
 - convert to phrases
 - labeling and generating training dataset
 
### [Part 2 : Building the NLP model](https://github.com/Sweetflowerjulia/NLP-Model_Text-Category-with-GloVe-and-LSTM/blob/master/NLP%20Model_Text%20multi-classification.ipynb)
 - load pre-trained GloVe word embeddings
 - tokenize the text
 - create embedding matrix
 - create Neural Network model in Keras 
   (embedding matrix - convolutional layer - LSTM - softmax)

### [Part 3 : Model deployment in Azure (Microsoft Web Service)](https://github.com/Sweetflowerjulia/NLP-Model_Text-Category-with-GloVe-and-LSTM/blob/master/Deploy%20NLP%20Model%20to%20Azure.ipynb)
 - Create Workspace
 - Pickle the model
 - Register the model
 - Create Image
 - Deploy WebService
 - Test calling web service

