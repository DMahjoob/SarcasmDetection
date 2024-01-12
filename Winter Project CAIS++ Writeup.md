Darius Mahjoob (collaborated with Stan Loosmore on idea brainstorming)
dmahjoob@usc.edu Dataset: News Headlines for Sarcasm Detection (NLP
Binary Classification) Sarcasm Detection Project Outline: In this
project, the objective is to develop a machine learning/deep learning
model for sarcasm detection in news headlines. The dataset comprises
headlines from TheOnion and HuffPost, and the goal is to classify
headlines as sarcastic (1) or not (0). The preprocessing steps used in
this project involved loading the dataset, handling missing values,
cleaning up the data, and tokenizing headlines using a suitable
tokenizer. The dataset was already split into training and testing sets,
but had to be converted to a .csv format to decrease development errors.
For the model development, I opted for a BERT transformer model specific
hyperparameters to incorporate the article_links and headline_names data
that were provided. The training procedure involved building the model
on the training set with validation on a separate set to prevent
overfitting. This choice aligns with the task\'s requirements,
leveraging BERT's ability to understand ambiguous patterns in text. The
evaluation metrics that I used to analyze the model included accuracy,
precision, recall, and F1-score, with the model achieving a test
accuracy of 100% with the given test data. This project\'s methodology
therefore ensures an absolute fit for sarcasm detection, considering the
limited dataset, BERT's strengths in handling data in context, and
well-chosen hyperparameters. The model\'s potential applications extend
beyond sarcasm detection, contributing to content analysis or even
potentially misinformation detection in news articles. However,
limitations may arise from the dataset\'s nature and potential
challenges with new sources or evolving language trends. As an example,
only two article types were used (Huffington Post and the Onion) which
saturated the data that was used and made it possible that the model was
learning strictly from the domain of the article link as opposed to
headline content. For future steps, exploring more advanced transformer
architecture models such as DistilBert, incorporating additional
features or contextual information, and expanding the dataset to include
other article sources for better generalization are essential. As is,
this project lays the foundation for a satisfactory sarcasm detection
model for news headlines, with broader implications for political and
social application in the future.
