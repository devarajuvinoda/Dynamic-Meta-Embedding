# Dynamic-Meta-Embedding
Dynamic Meta-Embedding for improved sentence representations:
 * An approach to using word embeddings for natural language processing (NLP) that dynamically selects the right types of embeddings for the task at hand.
 * It improves efficiency and overall performance by training a neural network on multiple embeddings, allowing the system to determine the usefulness of each embedding to understand language related to a given task.

Following are the results obtained for Sentiment Analysis task on [Movie Review Data](https://www.cs.cornell.edu/people/pabo/movie-review-data/),

  * Pretrained - Fasttext:
    * Test Accuracy: 0.8177
  * Pretrained - Word2vec:
    * Test Accuracy: 0.7948
  * Pretrained - Glove:
    * Test Accuracy: 0.8099
  * Word2Vec - gensim:
    * Test Accuracy: 0.7262
  * Fasttext - gensim:
    * Test Accuracy: 0.7413
  * **Dynamic Meta Embedding(DME):**
    * **Test Accuracy: 0.8785**


Reference:
* [Dynamic Meta-Embeddings for Improved Sentence Representations](https://arxiv.org/abs/1804.07983) by Douwe Kiela, Changhan Wang, Kyunghyun Cho

NOTE: The dataset contains 5331 positive and 5331 negative examples in two different files. The last 831 examples from each file was used as a test set (Total test set size 1662).
