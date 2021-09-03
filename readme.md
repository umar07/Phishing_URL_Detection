### Phishing URL Detection

This is an implementation of the paper -**"Phishing URL detection system based on URL features using SVM"** (http://eses.net.in/documents/paper5.2.3.pdf). Please cite this for any usage.
The dataset used for this is taken from here - https://www.kaggle.com/siddharthkumar25/malicious-and-benign-urls

The dataset is different from the one mentioned in the paper. However, the feature extraction process and the svm classification is the same. We have used 104,437 phishing urls and 104,438 genuine urls, in total 208,875 urls. We have extracted 18 features f1 to f18, and used all for the classification while in the paper they only proceeded with using the first 15 features.
The slight difference in result accuracy(99.24%) is due to a much bigger, different dataset.
