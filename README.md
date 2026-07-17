# MLP_maize_multiomics
A MLP that predicts the gene-level average multi-omics signal in maize after heat stress.

## Code description

01.MLP_multi.ipynb uses multi-omics data in CK condition to predict HS multi-omics data
02.MLPatac.ipynb uses the differential multi-omics information between CK and HS to predict the gene-level average chromatin accessibility signal after heat stress


## Software environment

The analyses were performed in the following environment:

- Operating system: Linux-3.10.0-957.el7.x86_64-x86_64-with-glibc2.17
- Python: 3.10.17 | packaged by conda-forge | (main, Apr 10 2025, 22:19:12) [GCC 13.3.0]
- NumPy: 1.23.5
- PyTorch: 2.6.0+cu118
- CUDA: 11.8
- cuDNN: 90100
- GPU: NVIDIA A40

The required Python packages are listed in `requirements.txt`.
A complete record of the original computational environment is provided in
`requirements-full.txt`.
