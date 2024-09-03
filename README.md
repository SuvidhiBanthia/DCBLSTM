# DCBLSTM

Protein Secondary Structure Prediction (PSSP) is a crucial task in computational biology that involves predicting the local spatial arrangement of amino acids in a protein based on its primary sequence. This information is vital for understanding protein function, stability, and interactions, and plays a significant role in various fields such as drug design, protein engineering, and genetic engineering.

This repository contains the datasets and model architecture used in the research project "DCBLSTM - Deep Convolutional Bidirectional Long Short-Term Memory Neural Network for Q8 Secondary Protein Structure Prediction". The model architecture is specified in [model.png](https://github.com/SuvidhiBanthia/DCBLSTM/blob/main/model.png). It leverages the power of bidirectional LSTMs to capture long-range dependencies between amino acids and CNNs to extract local features, enhancing the model's ability to learn spatial patterns.

The model is evaluated on three benchmark datasets: CB513, CASP10, and CASP11, which achieve accuracies of 88.9%, 83.9%, and 84.3%, respectively. The results demonstrate that DCBLSTM achieves state-of-the-art accuracy in Q8-state classification, outperforming existing methods.

### Dataset Structure
The project contains the following datasets within the datasets folder:
* Training data: CULLPDB (Filtered)
* Testing data: CASP10, CASP11, CB513
