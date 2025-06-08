# ResDW-GNN:  An Enhanced Residual Learning Framework for Graph Neural Networks based on Dual Random Walk
Official Implementation for the Knowledge-Based Systems 2025 paper, *ResDW-GNN: An Enhanced Residual Learning Framework for Graph Neural Networks based on Dual Random Walk*, by Jin Fan, Zhangyu Gu, Jiajun Yang, Huifeng Wu, Danfeng Sun, Jia Wu.

## 1. Introduction

To address the modeling challenges in both homogeneous and heterogeneous graph structures, we propose ResDW-GNN, a novel framework that integrates five synergistic components: a dual random walk strategy combining BFS and DFS sampling, a Dual-walk Node Representation (DNR) mechanism for learning node-level weights from different structural perspectives, an Adaptive Multi-Channel Fusion module, a Hybrid Residual Connections (HRC) mechanism, and an Adaptive Iterative Graph Convolution (AIGC) module.
The organic integration of these five core modules substantially enhances the framework's graph representation learning capabilities, enabling effective performance on both homophilous and heterophilous networks.
### 1.1 Framework

![ResDW-GNN](./model.pdf)

## 2. Code Link
You can download code from 
[link](https://pan.baidu.com/s/1Lp31eiGNpt8NBGof63-5TA?pwd=gzy2), 
password: gzy2 


## 3. Requirements

pip install -r requirements.txt
```
torch
torch-geometric
dgl
```

## 4. Train Model
You can run ```train.py``` to train **ResDW-GNN** in default settings on ```Cora```. 

Or run:

```
$ python train.py --dataset cora
```

You can modify the hyper-parameters settings in ```config.py```.

## 5. Contact

Please contact **Zhangyu Gu** (guzhangyu@hdu.edu.cn) if you have any question about this code.
