

## Quora_deduplication_flair.ipynb: To Identify Similar Question Pairs. Applied Siamese Network a special type of neural network which consists of two identical neural networks, each taking one of the two input question pairs. The last layers of the two networks are then fed to a Manhattan lstm model, which predicts the similarity between the two inputs using Flair Embeddings.


## Quora_deduplication_Glove.ipynb: To Identify Similar Question Pairs. Applied Siamese Network a special type of neural network which consists of two identical neural networks, each taking one of the two input question pairs. The last layers of the two networks are then fed to a Manhattan lstm model, which predicts the similarity between the two inputs using Glove Embeddings.


Data-------------------------------Quora Question Pairs Dataset

#Architecture Considered  ---------SIAMESE NEURAL NETWORK WITH LSTM 





Distance ---------------------------Manhattan Distance
#Loss function----------------------Mean Square Error

#Optimizer -------------------------Adam Optimizer



















## Pip Instructions
requires python3.5 above for flair 

pip install tensorflow;
pip install matplotlib;
pip install pandas;
pip install flair





