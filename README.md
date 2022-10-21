# Short-Answer-Evaluator
This project was done as part of Machine Learning Course at RVCE (Aug 2019)
Short answer evaluation problem solved using machine learning with Siamese LSTM networks.
The intention of this project is to automate the evalution of very short answer question. This is useful in case of 1 mark questions.

GloVe and Universal Sentence encoder are used as embeddings here. 
A siamese neural network, with input to first network being the encoded student's answer and the second one being the encoded teacher's reference answer.
A threshold is set and if the similarity between the student's answer and teacher's reference answer, then student's answer is marked as correct and is awarded one mark.
Future improvements in consideration : To consider the question and context of the question, while evatuating the answer.
