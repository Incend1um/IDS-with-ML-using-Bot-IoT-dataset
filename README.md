# IDS-with-ML-using-Bot-IoT-dataset
As part of university's final year project six classifiers were tested on Bot-IoT dataset (https://research.unsw.edu.au/projects/bot-iot-dataset):
<ul>
  <li> K-Nearest Neighbours (KNN)</li>
  <li> Gradient Boosing Machine (GBM)</li>
  <li> Random Forest (RF) </li>
  <li> Support Vector Machine (SVM) </li>
  <li> Adaboost </li>
  <li> Artificial Neural Networks (ANN), specifically Multi-Layer Perceptron (MLP) </li>
</ul>

This dataset comprises of realistic attack traffic, including<b> DoS & DDoS, port scanning, OS fingerprinting, keylogging, and data exfiltration</b>.

The Bot-IoT dataset is also imbalanced, hence, to increase the size of minority classes and to increase the overall efficiency of IDS, a method called Synthetic Minority Oversampling Technique (SMOTE) is employed. The results obtained through evaluation of binary and multi-class classifiers demonstrate a high classification accuracy. Using RF, it was possible to achieve 99.99% and 98.80% accuracy on the binary and multi-class classifications, respectively.

The approach: 
<br>
![Flowchart_ML_6](https://user-images.githubusercontent.com/64693248/164532991-634d2e0c-ee0c-4771-bebd-4dbc9f638d18.png)
