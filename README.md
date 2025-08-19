🧠 Model Training

The pre-trained classifiers were created using the following process:
1.  Dataset: The [Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) dataset from Kaggle.
2.  Feature Engineering: Comments were preprocessed and transformed into sentence vectors using average FastText embeddings.
3.  Training: A separate Logistic Regression model was trained for each of the six toxicity labels using Scikit-learn.
4.  Serialization: The trained models were saved using Python's pickle module for later use in the web app.


🔮 Future Improvements

- Experiment with deep learning models (e.g., LSTMs, Transformers/BERT) for improved accuracy.
- Add explainable AI (XAI) features to highlight which words contributed to the toxicity prediction.
- Implement a more sophisticated comment preprocessing pipeline (lemmatization, spell check).
- Dockerize the application for easier deployment.


🙏 Acknowledgments

- [FastText](https://fasttext.cc/) by Facebook AI Research for the pre-trained word vectors.
- [Streamlit](https://streamlit.io/) for the amazing framework to build interactive web apps.
- [Jigsaw/Google](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) for providing the dataset.
