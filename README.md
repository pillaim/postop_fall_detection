# Improving Postsurgical Fall Detection for Older Americans using LLM-driven Analysis of Clinical Narratives
This repository contains the code used for the paper titled "Improving postsurgical fall detection for older Americans using LLM-driven analysis of clinical narratives" by Pillai et al., published on [medRxiv](https://www.medrxiv.org/content/10.1101/2024.06.25.24309480v1)

## Overview
This project aims to enhance the detection of postsurgical falls in older adults through the analysis of clinical narratives using large language models (LLMs). The Mixtral-8x7B model demonstrated the best performance in predicting falls.

## Requirements
* Python 3.11
* Required Python packages are listed in requirements.txt

## Usage
The 0-shot and few-shot pipelines are provided in individual experiment notebooks. Please insert the path to your dataset to run the 0-shot code. To run the few-shot experiment, please insert the path to your dataset and incorporate your examples in the few-shot prompt.

## Citation
If you use this code in your research, please cite our paper:
```bibtex
@article{pillai2024fall_detection,
  title={Improving postsurgical fall detection for older Americans using LLM-driven analysis of clinical narratives},
  author={Pillai, Malvika and others},
  journal={medRxiv},
  year={2024},
  publisher={Cold Spring Harbor Laboratory}
}
```

## Contact
For any questions or issues, please contact Malvika Pillai, PhD (mpillai@stanford.edu).
