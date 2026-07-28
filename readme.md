**Fake Banknote Detector**

Build a model that predicts whether a banknote is genuine or forged.

This project lets you practise:

- Train/test splitting
- Cross-validation
- Confusion matrices
- Bias versus variance
- Feature scaling
- Comparing different models
- Deploying the chosen model through FastAPI

we mostly will be using Logistic Regression rather than Linear regression as it's prediction model.
Logistic Regression is a classification model.


*Your three models should therefore be:*

- Logistic Regression
- Support Vector Machine
- Random Forest Classifier


**Project question**

Given four measurements extracted from a banknote image, can the model determine whether the banknote is genuine or forged?

Your four inputs will be:

- Variance
- Skewness
- Curtosis
- Entropy

*Your output will be: Genuine or forged*


-----------------------------------------------------

*What you need before starting*

You already know enough to begin. Learn these ideas during the project:

- What X and y represent
- Classification versus regression
- Why training and test data must remain separate
- Basic pandas filtering and plotting
- Accuracy, precision, recall and F1-score
- Why SVM and Logistic Regression usually need feature - scaling
- What data leakage means

Scikit-learn recommends pipelines because they combine preprocessing and modelling while helping prevent test information from leaking into training. Scaling is particularly relevant for SVMs and regularised linear models.

**You do not need to learn these yet:**

- Mathematical derivations of SVM
- GridSearchCV
- PCA
- Feature engineering
- Deep learning
- Docker and cloud deployment
- Complicated MLOps
- Twenty different metrics

