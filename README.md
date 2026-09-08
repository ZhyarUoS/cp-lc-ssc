# Local Context and Contrastive Pre-training for Sequential Sentence Classification in Biomedical Abstracts

> **Status:** 📝 Submitted for review.

## Overview

This project proposes a simplified approach for sequential sentence classification in biomedical abstracts, combining contrastive pretraining (SimCSE) with local-context concatenation — evaluated against a single-sentence baseline and against a cross-attention architecture (CA-DSCA) across three biomedical PLMs (PubMedBERT, BioLinkBERT, BioBERT) on the PubMed 20k RCT benchmark.

## Repository Structure

```
cp-lc-ssc/
├── dataset/
│   ├── PubMed_20k_RCT/
│   │   ├── train.txt
│   │   ├── dev.txt
│   │   └── test.txt
│   └── unlabelled_dataset/
│       └── pubmed_abstracts_extracted_9996.csv
├── notebook/
│   └── sample.ipynb
├── published_cadsca_results/
│   └── published_cadsca_results.json
├── overview_of_the_proposed_approach/
│   └── approach.pdf
└── README.md
```

## Authors

- Zhyar Rzgar K. Rostam
- Gábor Kertész

Óbuda University

## Citation

To be added upon acceptance.
