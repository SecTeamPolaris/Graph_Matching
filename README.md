# Graph_Matching

Source code for **Robust Network Traffic Identification with Graph Matching**

The project is written in Python3.6.8 using the following backend: Intel i7-9750 @2.6GHz, 16GB RAM, NVIDIA GeForce RTX2060，Windows 10.

## Data

CrossNet2021 with two scenarios are involved, including  and ScenarioA and ScenarioB in [dataset](./dataset).

## Code 
Code is wiritten in Jupyter Notebook.

## Reference

'''
@article{LI2022109368,
title = {Robust network traffic identification with graph matching},
journal = {Computer Networks},
volume = {218},
pages = {109368},
year = {2022},
issn = {1389-1286},
doi = {https://doi.org/10.1016/j.comnet.2022.109368},
url = {https://www.sciencedirect.com/science/article/pii/S1389128622004029},
author = {Wenhao Li and Xiao-Yu Zhang and Huaifeng Bao and Qiang Wang and Zhaoxuan Li},
keywords = {Network traffic classification, Robustness analysis, Graph matching},
abstract = {Network traffic identification is of great value as an effective way for network management. Typically, intelligent classifiers are deployed for advanced network protection, including intrusion traffic detection and network behavior monitoring etc. Robust network traffic classifiers with generalization ability should also ensure stable performance in various network environments. Unfortunately, although the existing network traffic classifiers can achieve the claimed performance when initialized and tested in invariant network environments with stable attribute distributions, they are inclined to fail when adapting to varying practical networks and suffer from significant performance degradation. Based on analysis of representative state-of-the-art classifiers with respect to their transferability, we arrive at that feature distribution of the same class is vulnerable to the changes of networking which account for the degradation of most existing methods. To tackle the issues, we propose a weakly-supervised network traffic classification method based on graph matching. Specifically, network sessions are aggregated to several clusters with the extracted principal features through weakly-supervised clustering. Moreover, we measure the correlations between clusters from the same networks to construct the similarity graphs. Clusters from the testing network are associated with those from the initial network by the carefully designed graph matching algorithm, so that the testing clusters can be labeled according to the associated ones in the initialized network. Our method shows eye-catching robustness, achieving an accuracy of 88.19% when practically deployed in different networks, which significantly outperforms the existing approaches.}
}
'''
