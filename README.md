# Automated_Essay_Marking
Automated Essay Marking using Convolutional Neural Networks and Word Embeddings 

Supervisor: Dr. Frank C Langbein --

Moderator: Dr. Jing Wu --

Date of Submission: 11/05/2018 

ABSTRACT: The aim of this paper is to investigate the application of Machine Learning in Automated Essay Marking. After a thorough background of Machine Learning, Artificial and Convolutional Neural Networks and fundamental word-to-vector representations, six of the main approaches of an Automated Essay Marking system using Convolutional Neural Networks are presented. The approaches differ about the word-to-vector representation, the essay representation and the network structure they are using. The approaches are then implemented to different software versions and their implementation is fully explained. The results of the various versions are first presented and then evaluated using six different evaluation metrics such as Accuracy, Confusion Matrix, Loss Graph etc. The results are very encouraging with some of the versions classifying testing examples with an Accuracy of more than 50%, but most importantly capturing the dataset’s ordinal class structure. After evaluating the models and their results, the following outcomes were reached. The essay representation, as 1-dimensional or 2-dimensional, is insignificant given that the feature extraction part of the classification is performed with similar parameters. The word-to-vector representation is directly affecting the size of the essay and dimensions of the word-vector. As a result, a simpler word-to-vector representation can outperform a more complex word-to-vector representation, if the complex word-to-vector representation is not combined by a deep neural network that can “handle” its size.
