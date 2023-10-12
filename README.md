# Trojan-Detection-using-Binary-Classification

Introduction

In today's digitally interconnected world, the security of our digital systems is of paramount importance. Cyberattacks, particularly Trojan horse attacks, pose a significant threat to individuals, businesses, and governments. Trojans are malicious software that disguise themselves as harmless files or programs and can infiltrate systems when users unknowingly invite them, such as by visiting malicious websites or installing infected software. To effectively combat these attacks, it is essential to have robust methods for detecting and preventing them.

This repository contains a dataset that can be used to detect Trojan horse traffic through binary classification. The dataset consists of records of both malicious (Trojan) and benign network packets. By analyzing this data, you can build and evaluate models for the binary classification of network traffic into Trojan and Benign categories.

Dataset Information

Source: The dataset originates from the CIC website.

Size: The dataset comprises the following number of observations:

Trojan Data: 90,683 observations

Benign Data: 86,799 observations

Features

The dataset contains various features that can be used for the binary classification task. These features include:

Flow ID

Source IP

Source Port

Destination IP

Destination Port

Protocol

Timestamp

Flow Duration

Total Fwd Packets

Total Backward Packets

Total Length of Fwd Packets

Total Length of Bwd Packets

... and many more.

These features provide valuable information about network traffic characteristics, which can be leveraged for Trojan detection.

Usage

You can use this dataset to:

Train and evaluate machine learning models for binary classification (Trojan or Benign).

Explore the characteristics of Trojan and Benign network traffic.

Perform data analysis and visualization to gain insights into network traffic patterns.
