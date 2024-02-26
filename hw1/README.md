### 1. Download the dataset by the link "https://tinyurl.com/cs771-a23-hw1dat"

"""
### Brief description of Dataset -->

X_seen=np.load('X_seen.npy') 	(40 x N_i x D): 40 feature matrices. X_seen[i] is the N_i x D feature matrix of seen class i

Xtest=np.load('Xtest.npy')	(6180, 4096): feature matrix of the test data.

Ytest=np.load('Ytest.npy',)	(6180, 1): ground truth labels of the test data

class_attributes_seen=np.load('class_attributes_seen.npy')	(40, 85): 40x85 matrix with each row being the 85-dimensional class attribute vector of a seen class.

class_attributes_unseen=np.load('class_attributes_unseen.npy')	(10, 85): 10x85 matrix with each row being the 85-dimensional class attribute vector of an  unseen class.
"""

### 2. Place the dataset in working directory

### 3. run the file 'convex.ipynb' for method 1   
""" the code are explained with comments in code file itself"""

### 4. run the file 'regress.ipynb' for method 2
""" the code are explained with comments in code file itself"""
