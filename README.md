# pca_wrapper_model

Merging PCA and Wrapper Techniques for Anomaly Detection using Isolation Forest
This project is a demonstration of how to combine two techniques, PCA and wrapper, for anomaly detection using isolation forest. The code is implemented in Python and uses scikit-learn for PCA, wrapper, and isolation forest.

Installation
To run this code, you need to have Python 3 installed on your machine. You also need to install the following libraries:

numpy
pandas
scikit-learn
Dataset
The input data for this project is a simulated dataset that contains large samples with 82 features each. 

PCA and Wrapper Techniques
The PCA technique is used to reduce the dimensionality of the data by projecting it onto a lower-dimensional space. The wrapper technique is used to select the most relevant features for anomaly detection. These two techniques are combined to create a new feature space that captures the most important information in the data.

Isolation Forest
The isolation forest algorithm is used for anomaly detection. This algorithm creates a random forest of decision trees and uses the average path length to isolate anomalous samples. The isolation forest algorithm is fast and scalable and can handle high-dimensional data.

Results
The results of the anomaly detection using isolation forest are printed to the console. The code outputs the number of normal and anomalous samples, the precision and recall of the model, and the area under the ROC curve. The results show that the combined PCA and wrapper techniques improve the performance of the isolation forest algorithm for anomaly detection.

Conclusion
This project demonstrates how to combine two techniques, PCA and wrapper, for anomaly detection using isolation forest. The results show that this approach can improve the performance of the isolation forest algorithm for detecting anomalies in high-dimensional data.
