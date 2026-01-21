# Benchmarking Predict-then-Optimize (PtO) Problems

## About
This project based on this [paper](https://arxiv.org/abs/2311.00983) and forked from this [repository](https://github.com/PredOpt/predopt-benchmarks). I am fixing some bugs and decide to optimize them to Windows platform (with PyCharm tested).

Now:
- [ ] Energy
- ......

## Installation

Based on Python 3.8

1. Install Conda by following the [official installation guide](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

2. Create and activate the environment:
```bash
# Create environment
conda env create -n optenv python=3.8 -y

# Activate
conda activate benchmarking_env

# Package install
pip install -r requirements.txt
pip install pytorch-lightning==1.6.4
```

## Cite
```bibtex
@article{mandi2024decision,
  title={Decision-focused learning: Foundations, state of the art, benchmark and future opportunities},
  author={Mandi, Jayanta and Kotary, James and Berden, Senne and Mulamba, Maxime and Bucarey, Victor and Guns, Tias and Fioretto, Ferdinando},
  journal={Journal of Artificial Intelligence Research},
  volume={80},
  pages={1623--1701},
  year={2024},
  doi={10.1613/jair.1.15320}
}
```
