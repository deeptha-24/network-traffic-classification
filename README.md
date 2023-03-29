# network-traffic-classification
The use of machine learning to classify netowrk traffic 
The dataset used in project was downloaded from Kaggle platform (https://www.kaggle.com/jsrojas/ip-network-traffic-flows-labeled-with-87-apps).


# 💻 Technologies used:
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

The Project aim is to analyze IP network traffic flows to predict application layer protocol (specific application) such as Facebook, YouTube, and Instagram.
The dataset used in project was downloaded from Kaggle platform (https://www.kaggle.com/jsrojas/ip-network-traffic-flows-labeled-with-87-apps).
Each instance holds the information of an IP flow generated by a network device i.e., source and destination IP addresses, ports, interarrival times, layer 7 protocol (application) used on the flow that we want to predict class.

#Motivation
Considering that most of the network traffic classification datasets are aimed only at identifying the type of application an IP flow holds (WWW, DNS, FTP, P2P, Telnet,etc), this dataset goes a step further by generating machine learning models capable of detecting specific applications such as Facebook, YouTube, Instagram, etc, from IP flow statistics (currently 75 applications).
