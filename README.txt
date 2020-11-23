pickle_in = open("X_train_rusb.pickle","rb")
X_train = pickle.load(pickle_in)

pickle_in = open("y_train_rusb.pickle","rb")
y_train = pickle.load(pickle_in)

pickle_in = open("X_test_rusb.pickle","rb")
X_test = pickle.load(pickle_in)

pickle_in = open("y_test_rusb.pickle","rb")
y_test = pickle.load(pickle_in)