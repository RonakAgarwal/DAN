
# Project Description

This project utilizes Natural Language Processing (NLP) and Machine Learning (ML) to predict answers to QuizBowl formatted questions. These questions provide an ascending series of clues for their answer.

The project includes a base class that is designed to guess the default guess. This is useful to test for important features for feature engineering. The class has several methods for training the guesser, finding phrases in the training questions, tokenizing the text, and generating a set of predictions for a list of questions.

The project also includes utility functions for calculating word overlap between a query and a page, and for printing out snippets of top guesses. The base class can be trained with a dataset, and it uses a tf-idf vectorizer to analyze the training dataset and to process future examples. It can also find phrases that often appear together in the training questions, which enhances its understanding of the context.

## Features

- **Text Analysis**: The project uses advanced text analysis techniques to understand and process questions.
- **Machine Learning**: The project utilizes machine learning algorithms to improve its guessing accuracy over time.
- **Phrase Detection**: The project can identify phrases that often appear together, enhancing its understanding of the context.
- **Batch Guessing**: The system can handle multiple questions at once, providing a set of predictions for each.
- **Utility Functions**: The project includes utility functions for calculating word overlap and for printing out snippets of top guesses.
