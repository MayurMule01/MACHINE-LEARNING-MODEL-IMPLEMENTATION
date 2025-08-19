# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*Company : CODTECH IT SOLUTION.

*NAME : MAYUR MADHAV MULE

*INTERN ID : CT04DH1761

*DOMAIN : PYTHON PROGRAMMING

*DURATION : 4 WEEKS

*MENTOR : NEELA SANTHOSH KUMAR

   In this project, we made a program that can check whether a message is spam (like fake offers, lottery messages, promotions) or not spam (normal messages from friends or work).

  We used a dataset that already has many messages marked as spam or not spam. First, we cleaned the data and kept only the important parts: the message text and its label. Since computers do not understand words directly, we changed the text into numbers using a method called CountVectorizer, which counts how many times each word appears.

  After preparing the data, we divided it into two parts: one for training and one for testing. We used a simple machine learning algorithm called Naive Bayes, which works very well for text problems.

Once trained, the model was tested and it gave us an accuracy score to show how correct the predictions were. We also checked a confusion matrix and report to see how many spam and not-spam messages were correctly identified.

At the end, we tried the model with our own sentences, like “You won a lottery ticket!” and the program was able to tell if it is spam or not.

This project is a small but clear example of how machine learning can be used in real life, such as email spam filters.
