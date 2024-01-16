# UNSW-NB-15-Dataset-Feed-Forward-ML-Model---Attack-Type-Classification
UNSW-NB 15 Dataset Feed Forward ML Model - Attack Type Classification
UNSW-NB15 is a network traffic data set with different categories for normal activities and synthetic attack behaviours.

This project includes a diffent approach to the classification model for UNSW-NB15 data set then before. This model developed using a random forest and feed-forward neural network. The system uses the random forest that classifies data to normal or malicious data. This information is then used to train a neural network to further classify the attack data to different attack categories.

Solves:Detailed clarification of what types of attacks your classification is likely to miss and how methods might be improved.

This notebook will the follwing machine learning methods:

Random Forest : For Attack or Normal Classifier
Feed Forward Neural Networks: For Attack Type Classifier
We will illustrate this ML model approach and compare the performances.

The raw network packets of the UNSW-NB 15 dataset was created by the IXIA PerfectStorm tool in the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS) for generating a hybrid of real modern normal activities and synthetic contemporary attack behaviours. Further information found at https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/








cpdump tool is utilised to capture 100 GB of the raw traffic (e.g., Pcap files). This dataset has nine types of attacks, namely, Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode and Worms. The Argus, Bro-IDS tools are used and twelve algorithms are developed to generate totally 49 features with the class label.

These features are described in UNSW-NB15_features.csv file.

The total number of records is 2,540,044 which are stored in the four CSV files, namely, UNSW-NB15_1.csv, UNSW-NB15_2.csv, UNSW-NB15_3.csv and UNSW-NB15_4.csv.

The details of the UNSW-NB15 dataset are published in following the papers:

Moustafa, Nour, and Jill Slay. "UNSW-NB15: a comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set)." Military Communications and Information Systems Conference (MilCIS), 2015. IEEE, 2015. Moustafa, Nour, and Jill Slay. "The evaluation of Network Anomaly Detection Systems: Statistical analysis of the UNSW-NB15 dataset and the comparison with the KDD99 dataset." Information Security Journal: A Global Perspective (2016): 1-14. Moustafa, Nour, et al. . "Novel geometric area analysis technique for anomaly detection using trapezoidal area estimation on large-scale networks." IEEE Transactions on Big Data (2017). Moustafa, Nour, et al. "Big data analytics for intrusion detection system: statistical decision-making using finite dirichlet mixture models." Data Analytics and Decision Support for Cybersecurity. Springer, Cham, 2017. 127-156.

For more information, please contact the authors: Harshil Patel & Yuesheng Chen are a students in Industrial Engineering at Ohio State University, and they are interested in new Cyber threat intelligence approaches and the technology of Industry 4.0.

In this notebook, the operations conducted include:

Preprocessing the data to prepare for training ML models.
Creating datsets for feed-forward ML model.
Training ML models based RM and ANN.
Evaluating ML model based on testing data.
