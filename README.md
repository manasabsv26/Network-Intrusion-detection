A **Network Intrusion Detection System (NIDS)** is a system that prevents the
network from possible intrusions by inspecting and analyzing the network
traffic, to maintain its confidentiality, integrity, and availability. NIDS is mainly
designed to detect system and intrusion attacks and classify system activities into
regular and abnormal form. 

## Project Overview
The analysis algorithm of our project focuses on the generic class imbalance problem
that results in giving quite low accuracy for minority attack samples. We aim to
solve it using the ** Hybrid Sampling** technique, which helps us achieve a balanced
dataset. This includes **One Side Selection(OSS)** for reducing noise samples
in majority category and **Synthetic Minority Over Sampling techniques(SMOTE)** for
increasing minority samples/ Along with this, we aim at achieving higher overall accuracy by proposing
a deep hierarchical framework which employs the use of **Convolutional Neural Network(CNN)** for extracting spatial features and **Bi-directional long short-term memory(Bi-LSTM)** for extracting the temporal features.
The main scope of this project is to take the packet data(network traffic)
as its input, and classify the data sample into one the five classes:Normal/Any of
the four attack classes.

Data Flow Diagram Level 1: 

![image](https://github.com/user-attachments/assets/24c00e43-a156-40b5-838e-472ea6482462)

Data Flow Diagram Level 2: 

![image](https://github.com/user-attachments/assets/01e1134e-a2d1-4be0-bdb6-b0f148295c0d)
