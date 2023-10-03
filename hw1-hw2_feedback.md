#Hw1- Very good.
Hw2 –  You should use threshold to decide to class. Other things is very good, thank you.
def predict(X, W, b):
    z = np.dot(X, W) + b
    y_pred = 1 / (1 + np.exp(-z))
    return np.round(y_pred).astype(int)
Thank you for your efforts :)
