---
layout: page
title: Projects
permalink: /Projects/
---

# Lab Research

- TS-RAG X: Historical Context-Enhanced Retrieved Augmentation Generation for Time Series Foundation Models. *In Progress* <br>

  **Description:** This project expands the capacity of [TS-RAG](https://arxiv.org/pdf/2503.07649) by Ning et al., a retrieval-augmented generation framework for enhancing the generalization and interpretability of Time Series Foundation Models (TSFMs), by introducing the retrieved historical contexts in the augmentation module. TS-RAG X enables retrieval of semantically relevant segments from a dedicated knowledge base through incorporating both context windows and their associated future horizons.

  I am fortunate to conduct this project under the guidance of [Professor Dongjin Song](https://songdj.github.io) funded through an NSF Research Experience for Undergraduates (REU) supplement.

# Class Projects

- Memory-Augmented Variational RNN (MVRNN) [[GitHub]](https://github.com/uladcharn/fmRNN-fmLSTM) <br> 

  **Description:** This project presents **Memory-Augmented Variational RNN (MVRNN)**, a generative neural network with the cross-modified cell structure design of existing [Memory-Augmented RNN (MRNN)](https://arxiv.org/pdf/2006.03860) by Zhao et al. and [Variational RNN (VRNN)](https://arxiv.org/pdf/1506.02216) by Chung et al. The proposed neural network demonstrates a performative advantage from extracting the long-memory effect from data and modeling variability, outperforming existing recurrent network baselines by about 7% on average across several stock price volatility datasets.

- Filter Bank-Embedded MRNN (F-MRNN) and MLSTM (F-MLSTM) [[GitHub]](https://github.com/uladcharn/fmRNN-fmLSTM) [[PDF]](/folder1/STAT_4195_Final_Project.pdf) <br>

  **Description:** The MRNN/MLSTM networks have significantly improved the ability of recurrent networks to handle the long-range dependence data with their novel long-memory filter component, whose weights decay at a polynomial rate. Signal processing techniques, such as filter banks, have been effectively used in time series analysis to extract relevant features on varying frequency scales. This project extends the definition of memory-augmented by requiring the model to process the data through multiple long-memory filters. The proposed approach uplevels the original ability of original MRNN/MLSTM to process the long-memory sequences by allowing these networks to learn the best combination of filters to use for data processing.

  
