# Word embeddings with neural networks

Learn about how word embeddings carry the semantic meaning of words, which makes them much more powerful for NLP tasks, then build your own Continuous bag-of-words model to create word embeddings from Shakespeare text.

## Learning Objectives

- Gradient descent
- One-hot vectors
- Neural networks
- Word embeddings
- Continuous bag-of-words model
- Text pre-processing
- Tokenization
- Data generators

## Lecture: Word Embeddings

- [Video - Week Introduction](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/rOjVO/week-introduction)

- [Video - Overview](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/4k0An/overview)

- [Reading - Overview](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/Zij4F/overview)

- [Video - Basic Word Representations](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/Lkuce/basic-word-representations)

- [Reading - Basic Word Representations](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/YY3Fl/basic-word-representations)

- [Video - Word Embeddings](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/YC0Un/word-embeddings)

- [Reading - Word Embeddings](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/VJeEP/word-embeddings)

- [Video - How to Create Word Embeddings](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/a6J0B/how-to-create-word-embeddings)

- [Reading - How to Create Word Embeddings](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/d57hd/how-to-create-word-embeddings)

- [Video - Word Embedding Methods](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/wxlIv/word-embedding-methods)

- [Reading - Word Embedding Methods](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/tI0jL/word-embedding-methods)

- [Video - Continuous Bag-of-Words Model](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/hW72r/continuous-bag-of-words-model)

- [Reading - Continuous Bag-of-Words Model](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/FD4DO/continuous-bag-of-words-model)

- [Video - Cleaning and Tokenization](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/LnHR0/cleaning-and-tokenization)

- [Reading - Cleaning and Tokenization](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/2gS0p/cleaning-and-tokenization)

- [Video - Sliding Window of Words in Python](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/GrY5v/sliding-window-of-words-in-python)

- [Reading - Sliding Window of Words in Python](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/nXUrW/sliding-window-of-words-in-python)

- [Video - Transforming Words into Vectors](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/gCkdx/transforming-words-into-vectors)

- [Reading - Transforming Words into Vectors](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/n2LS9/transforming-words-into-vectors)

- [Lab - Lecture Notebook - Data Preparation](./Labs/C2_W4_lecture_nb_1_data_prep.ipynb)

- [Video - Architecture of the CBOW Model](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/UiH4B/architecture-of-the-cbow-model)

- [Reading - Architecture of the CBOW Model](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/GTYeE/architecture-for-the-cbow-model)

- [Video - Architecture of the CBOW Model: Dimensions](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/2iBbs/architecture-of-the-cbow-model-dimensions)

- [Reading - Architecture of the CBOW Model: Dimensions](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/l1ucn/architecture-of-the-cbow-model-dimensions)

- [Video - Architecture of the CBOW Model: Dimensions 2](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/bUzQu/architecture-of-the-cbow-model-dimensions-2)

- [Reading - Architecture of the CBOW Model: Dimensions 2](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/0kvxU/architecture-of-the-cbow-model-dimensions)

- [Video - Architecture of the CBOW Model: Activation Functions](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/DLyPe/architecture-of-the-cbow-model-activation-functions)

- [Reading - Architecture of the CBOW Model: Activation Functions](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/WqIgG/architecture-of-the-cbow-model-activation-functions)

- [Lab - Lecture Notebook - Intro to CBOW model](./Labs/C2_W4_lecture_nb_2_intro_to_CBOW.ipynb)

- [Video - Training a CBOW Model: Cost Function](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/N1pEX/training-a-cbow-model-cost-function)

- [Reading - Training a CBOW Model: Cost Function](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/sfiuP/training-a-cbow-model-cost-function)

- [Video - Training a CBOW Model: Forward Propagation](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/Vphwi/training-a-cbow-model-forward-propagation)

- [Reading - Training a CBOW Model: Forward Propagation](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/sD7Jz/training-a-cbow-model-forward-propagation)

- [Video - Training a CBOW Model: Backpropagation and Gradient Descent](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/mPJwt/training-a-cbow-model-backpropagation-and-gradient-descent)

- [Reading - Training a CBOW Model: Backpropagation and Gradient Descent](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/EEbAq/training-a-cbow-model-backpropagation-and-gradient-descent)

- [Lab - Lecture Notebook - Training the CBOW model](./Labs/C2_W4_lecture_nb_3_training_the_CBOW.ipynb)

- [Video - Extracting Word Embedding Vectors](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/Py1VW/extracting-word-embedding-vectors)

- [Reading - Extracting Word Embedding Vectors](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/effZO/extracting-word-embedding-vectors)

- [Lab - Lecture Notebook - Word Embeddings](./Labs/C2_W4_lecture_nb_4_word_embeddings_hands_on.ipynb)

- [Video - Evaluating Word Embeddings: Intrinsic Evaluation](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/BELqR/evaluating-word-embeddings-intrinsic-evaluation)

- [Reading - Evaluating Word Embeddings: Intrinsic Evaluation](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/b26Xq/evaluating-word-embeddings-intrinsic-evaluation)

- [Video - Evaluating Word Embeddings: Extrinsic Evaluation](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/SEJkb/evaluating-word-embeddings-extrinsic-evaluation)

- [Reading - Evaluating Word Embeddings: Extrinsic Evaluation](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/np9nb/evaluating-word-embeddings-extrinsic-evaluation)

- [Lab - Lecture notebook: Word embeddings step by step](./Labs/C2_W4_lecture_nb_5_word_embeddings_step_by_step.ipynb)

- [Video - Conclusion](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/r7XXs/conclusion)

- [Reading - Conclusion](https://www.coursera.org/learn/probabilistic-models-in-nlp/supplement/aIneD/conclusion)

- [Video - Week Conclusion](https://www.coursera.org/learn/probabilistic-models-in-nlp/lecture/FRqTy/week-conclusion)

## Lecture Notes (Optional)

- [Reading - Lecture Notes W4](./Readings/C2_W4.pdf)

## Assignment: Word Embeddings

- [Lab - Word Embeddings](./Labs/C2_W4_Assignment.ipynb)
