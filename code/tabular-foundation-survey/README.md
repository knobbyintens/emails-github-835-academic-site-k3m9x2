# A Survey of Tabular Foundation Models under Distribution Shift

Official code release for the paper "A Survey of Tabular Foundation Models under Distribution Shift" (Jose Anderson et al.).

## Release Status

This code release is public and usable. You can download it, run the training
scripts and reproduce the experiments reported in the paper.

## Overview

This release contains the model implementation, training scripts and
evaluation utilities used in the paper.

## Project Structure

```
├── src/
│   ├── model.py
│   ├── train.py
│   └── utils.py
├── data/
├── experiments/
├── notebooks/
├── results/
└── tests/
```

## Getting Started

```bash
pip install -r requirements.txt
```

Run the training entry point with the default configuration in
`experiments/default.yaml`.

## Citation

If you use this code, please cite the paper.
