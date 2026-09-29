# ml-mac-mini

Machine learning experiments running locally on a Mac mini (Apple Silicon).

## Goals

- Train and fine-tune small models on-device using the Apple GPU (Metal / MPS)
- Benchmark local inference for open-weight models
- Keep experiments reproducible and lightweight

## Setup

```bash
git clone https://github.com/egil10/ml-mac-mini.git
cd ml-mac-mini
python3 -m venv .venv
source .venv/bin/activate
```

Verify that PyTorch can see the Apple GPU:

```python
import torch
print(torch.backends.mps.is_available())
```

## Structure

```
ml-mac-mini/
├── README.md
└── .gitignore
```

More to come.
