# QM9 GNN: Utilizing Graph Neural Networks to Predict Chemical Properties

![PyTorch](https://img.shields.io/badge/PyTorch-203858?style=flat-square)
![PyTorch Geometric](https://img.shields.io/badge/PyTorch%20Geometric-203858?style=flat-square)
![GCN](https://img.shields.io/badge/GCN-203858?style=flat-square)
![GATv2](https://img.shields.io/badge/GATv2-203858?style=flat-square)
![RDKit](https://img.shields.io/badge/RDKit-203858?style=flat-square)

This notebook compares graph convolutional and graph attention models for HOMO-LUMO gap prediction on QM9. It uses PyTorch Geometric for the GCN and GATv2 architectures, with RDKit descriptors to examine prediction errors by molecular structure.

Overall performance hides larger errors for aromatic and heteroatom-rich molecules. Attention improves predictions selectively in these groups, so the analysis looks at chemical structure as well as aggregate metrics. The training, prediction plots and descriptor-based error analysis are in `QM9_GNN_2D_Baseline.ipynb`.

