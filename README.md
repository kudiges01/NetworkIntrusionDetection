### Network Intrusion Detection
Application of machine learning techniques to determine intrusion detection in networks

**Author**
Sid Kudige

#### Executive summary

- Billions in losses every year in organizations due to Cyberattacks
- Intrusion Detection is critically important to prevent Cyberattacks
- Commercially available IDS can detect many attacks but may miss some attacks 
- A machine learning approach to intrusion detection using classification can be a cost effective technique for organizations in classifying network traffic as safe and not safe

#### Rationale
Why should anyone care about this question?

- To help prevent massive economic losses due to Cyberattacks

#### Research Question
What are you trying to answer?

- Use machine learning classification models to classify network traffic as "Safe" or "Not safe"

#### Data Sources
What data will you use to answer you question?

- https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection

#### Methodology
What methods are you using to answer the question?

The following Machine Learning classification models will be used to classify network traffic as "Safe" or "Not safe"

   Naive Bayes - BernoulliNB
   
   Decision Tree Classifier
   
   Random Forest Classifier
   
   XGB Classifier
   
   Bagging Classifier
   
   AdaBoostClassifier

   Neural Networks - Keras Sequential Classifier

#### Results
What did your research find?

BaggingClassifier, Random Forest Classifier and XGB Classifier perform very well and they can detect intrusions and anamolies with over 99.5% accuracy.

The Neural network Keras model also performs well and it can detect intrusions and anomalies with 97.9% accuracy. 

This demonstrates the viablity of using machine learning models to detect intrusions in networks on a very large scale. These same machine learning models can also be used on real time network traffic to detect intrusion in a time sensitive manner so that organizations can be protected instantly from malicious actors using network instrusion attacks.

#### Next steps
What suggestions do you have for next steps?

These AI/ML models must be scaled and deployed at a large scale using massive compute on the public cloud so that they can be used to detect intrusions on a real time basis on network traffic. This will help organizations respond immediately to cyber threats.

#### Outline of project

- Notebook location for the classifiers - https://github.com/kudiges01/NetworkIntrusionDetection/blob/main/Intrusion_Detect.ipynb
- Notebook location for the Neural network - https://github.com/kudiges01/NetworkIntrusionDetection/blob/main/Intrusion_Detect_Keras.ipynb

##### Contact and Further Information
Sid Kudige 
