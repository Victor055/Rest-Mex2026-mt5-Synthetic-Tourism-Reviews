# Rest-Mex2026-mt5-Synthetic-Tourism-Reviews
Official implementation of the LynxesAI-LKEBUAP team for REST-MEX 2026.

## Overview

This repository contains the implementation of our approach for synthetic tourism review generation using instruction-based fine-tuning of mT5 and a RoBERTa-based sentiment classifier.

## Repository

```
notebooks/
├── 01_mt5_generation.ipynb
└── 02_roberta_classifier.ipynb
```

- **01_mt5_generation.ipynb**: Fine-tuning of mT5 and conditional generation of synthetic tourism reviews.
- **02_roberta_classifier.ipynb**: Fine-tuning of a RoBERTa classifier for sentiment prediction and candidate selection.

## Requirements

Install the required libraries with:

```bash
pip install -r requirements.txt
```

## Dataset

The official REST-MEX 2026 dataset is not distributed in this repository and must be obtained from the shared task organizers.

## Citation

If you use this repository, please cite our REST-MEX 2026 paper.

```bibtex
@inproceedings{morales2026,
  title={LynxesAI-LKEBUAP at REST-MEX 2026: Sentiment Analysis with Synthetic Tourism Reviews using Transformer-Based Conditional Generation and Filtering},
  year={2026}
}
```

## License

MIT License.
