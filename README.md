# ParaChecker-using-DeepLearning
ParaChecker: Elevating Paraphrase Detection Using Deep Learning 

Quora is a widely used question-and-answer platform that facilitates knowledge sharing and discussions on a multitude of topics. With a vast number of users, it’s common for multiple questions to arise from different users with similar intents. Platforms like Quora play a crucial role in ensuring high-quality content is made available to users. By identifying semantically identical questions based on their intent, we can significantly enhance the overall user experience. 

This project focuses on finding pairs of semantically identical questions using deep learning models to address a binary classification challenge. To improve consistency, the dataset is preprocessed using various Natural Language Processing techniques. We then train deep learning models, specifically the Gated Recurrent Unit (GRU) and Long Short-Term Memory (LSTM) models, in a Siamese architecture, employing GLoVe (Global Vectors for Word Representation) and Word2Vec (Word to Vector) embedding methods, respectively. The LSTM model with Word2Vec achieved an impressive accuracy of 83.30%, outperforming the GRU model.


