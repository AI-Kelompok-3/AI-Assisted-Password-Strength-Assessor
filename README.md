**Introduction**

Password strength assessment is critical to cybersecurity, ensuring users create robust passwords that are difficult to crack. This project compares machine learning and AI models to determine which is most effective at assessing the strength of passwords.

We analyze models based on their ability to predict strength levels (weak, moderate, strong) by considering various features like password length, the use of special characters, numbers, and sequences of letters or numbers.


**Models**

The following AI models are compared:
1. Naive Bayes
2. Logistic Regression
3. Stochastic Gradient Descent
4. Passive Aggressive Classifier
Each model is trained on a common dataset and evaluated on how accurately it classifies password strength.


**Dataset**

The dataset used in this project consists of real-world and synthetic passwords labeled as weak, moderate, or strong. Passwords are evaluated based on length, character diversity, entropy, dictionary word usage, and other security heuristics. The dataset is divided into training and testing sets with features extracted from each password.
Dataset link: https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset/


**Evaluation Metrics**

The models are evaluated using the following metrics:
1. Accuracy: The percentage of correct predictions made by the model.
2. Precision: The number of true positives divided by the sum of true and false positives.
3. Recall: The number of true positives divided by the sum of true positives and false negatives.
4. F1 Score: The harmonic mean of precision and recall.
5. ROC-AUC: Area under the receiver operating characteristic curve, which indicates the model’s ability to distinguish between weak and strong passwords.
