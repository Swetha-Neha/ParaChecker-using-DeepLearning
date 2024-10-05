# ParaChecker-using-DeepLearning
ParaChecker: Elevating Paraphrase Detection Using Deep Learning 

Quora is a widely used question-and-answer platform that facilitates knowledge sharing and discussions on a multitude of topics. With a vast number of users, it’s common for multiple questions to arise from different users with similar intents. Platforms like Quora play a crucial role in ensuring high-quality content is made available to users. By identifying semantically identical questions based on their intent, we can significantly enhance the overall user experience. 

This project focuses on finding pairs of semantically identical questions using deep learning models to address a binary classification challenge. The dataset is preprocessed using various Natural Language Processing techniques to improve consistency. We then train deep learning models, specifically the Gated Recurrent Unit (GRU) and Long Short-Term Memory (LSTM) models, in a Siamese architecture, employing GLoVe (Global Vectors for Word Representation) and Word2Vec (Word to Vector) embedding methods, respectively. The LSTM model with Word2Vec achieved an impressive accuracy of 83.30%, outperforming the GRU model.


<img width="1245" alt="image" src="https://github.com/Swetha-Neha/ParaChecker-using-DeepLearning/blob/main/AD_4nXeo-Fy883TFTPk180ygDnTGucNEvNdCyFxN0tn2prsCEpG9sOV1xn2qO-tNJQp0Ij9X9PLcNIMeH6EXraApaIwdBYybe14q-obrmwdU3NxYSiY1_8K4ftAP.jpeg?raw=true">



The performance of the models is evaluated using Accuracy, Precision, Recall, and F1 score. Based on the quantitative values, LSTM using Word2VEc embedding outperformed GRU using GLoVE embedding across all evaluation metrics. The LSTM model achieved an Accuracy of 83.30%, a precision of 84%, a Recall of 83%, and an F1 score of 83%. On the other hand, GRU with Glove achieved 77.34% accuracy, precision of 78%, recall of 77% and F1 score of 78%. Based on the evaluation metric, the LSTM model is effective in identifying duplicate questions. 


