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

- Memory-Augmented Variational RNN (MVRNN) [[GitHub]](https://github.com/uladcharn/MVRNN) [[PDF]](/folder1/CSE 5825 - Project 3 (final).pdf) <br> 

  **Description:** This project presents **Memory-Augmented Variational RNN (MVRNN)**, a recurrent network with the cross-modified cell structure design of existing [Memory-Augmented RNN (MRNN)](https://arxiv.org/pdf/2006.03860) by Zhao et al. and [Variational RNN (VRNN)](https://arxiv.org/pdf/1506.02216) by Chung et al. While these approaches address distinct limitations of conventional recurrent networks, each exhibits deficiencies that the other addresses: neither alone can capture the full complexity of temporal data with both long-range dependence and high variability across input data.

  The proposed neural network is capable of capturing long-range dependence and simultaneously modeling complex multimodal distributions for processing latent variabilities emerging in real-world data. The proposed MVRNN demonstrates a performative advantage from modeling long memory patterns and latent variability across data, outperforming MRNN baselines by approximately 7-10% on average across several stock price volatility datasets.

- Filter Bank-Embedded MRNN (F-MRNN) and MLSTM (F-MLSTM) [[GitHub]](https://github.com/uladcharn/fmRNN-fmLSTM) [[PDF]](/folder1/STAT_4195_Final_Project.pdf) <br>

  **Description:** The [MRNN/MLSTM](https://arxiv.org/pdf/2006.03860) networks by Zhao et al. have significantly improved the ability of recurrent networks to handle the long-range dependence in data with their novel long memory filter component, whose weights decay at a polynomial rate. Signal processing techniques, such as filter banks, have been effectively used in time series analysis to extract relevant features on varying frequency scales.

  This project extends the definition of memory-augmented recurrent networks by introducing Filter Bank-Embedded MRNN (F-MRNN) and MLSTM (F-MLSTM) requiring the model to process the data through multiple long memory filters. The proposed approach uplevels the original ability of original MRNN/MLSTM to process the sequences with long-range dependence by allowing these networks to learn the best combination of filters to use for data processing.

  
