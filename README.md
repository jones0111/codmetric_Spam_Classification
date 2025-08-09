SMS Spam Detection

Project Description:
This project implements an SMS Spam Classifier using Python and Scikit-learn.
It loads the SMS Spam Collection dataset, performs text preprocessing (cleaning, tokenization, vectorization), trains a classification model (Logistic Regression), and evaluates performance using accuracy score and a confusion matrix visualization.

Libraries Used:
Pandas - Data loading & manipulation
NumPy - Numerical computations
NLTK - Natural Language Processing (tokenization, stopword removal)
Scikit-learn - Machine learning model training & evaluation
Matplotlib / Seaborn - Data visualization & confusion matrix

Output Example
Model accuracy score:
Accuracy on training data: 0.9676912721561588
Accuracy on testing data: 0.9668161434977578

Confusion matrix visualization
Matrix for training data:
[[ 452  140]
 [  4  3861]]

Matrix for testing data:
[[118  37]
 [ 0  960]]

Spam/Ham classification results
input_mail : Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005. Text FA to 87121 to receive entry question(std txt rate)T&C's apply 08452810075over18's
Predicted : Spam

input_mail : I've been searching for the right words to thank you for this breather. I promise i wont take your help for granted and will fulfil my promise. You have been wonderful and a blessing at all times.
Predicted : Not Spam



