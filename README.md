# BM-Diagnosis: Two-Stage Interpretable Deep Learning for Bone Marrow Disease Classification

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
[![R-4.3.0](https://img.shields.io/badge/R-%E2%89%A54.3.0-%23276DC3.svg?style=flat&logo=r&logoColor=white)](https://cran.r-project.org/bin/windows/base/old/4.3.0/) 
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/) 
[![Nextflow](https://img.shields.io/badge/nextflow-%3E%2023.10-099acd.svg)](https://www.nextflow.io) 
[![Snakemake](https://img.shields.io/badge/snakemake-%E2%89%A57.32-brightgreen.svg)](https://snakemake.readthedocs.io)
[![PyTorch Version](https://img.shields.io/badge/pytorch-1.12%2B-orange)](https://pytorch.org/)

**Repository**: <https://github.com/JhuangLab/BMSGC>

**Principal Investigator**: Jhuanglab

**Contact**: hiekeen $$at$$ gmail.com

### The source code will be made available following the manuscript's publication.

## Project Overview

Accurate diagnosis of bone marrow diseases from hematoxylin-eosin (HE)-stained whole-slide images (WSIs) remains challenging due to diffuse growth patterns, complex spatial heterogeneity, and overlapping morphological features. This repository implements an interpretable two-stage deep learning framework that closely mirrors the routine pathological diagnostic workflow, enabling automated, robust, and clinically aligned classification of bone marrow disorders.

### Key Features

-   🔀 Two-Stage Diagnostic Pipeline: Mimics real-world clinical workflow
Stage 1: Normal vs. Abnormal screening → Stage 2: Disease subtyping
-   🌐 Region-Aware Graph Modeling: Captures spatial heterogeneity and long-range tissue topology for superior feature aggregation
-   📉 Distribution-Robust: Minimal performance degradation across temporal and cross-institutional shifts
-   🔍 Built-in Interpretability: Region-level attention maps highlight diagnostically relevant morphological patterns
-   🏥 Clinical-Ready Design: Optimized for integration into digital pathology pipelines



### Clone the Repository

git clone [https://github.com/JhuangLab/BMSGC.git](https://github.com/JhuangLab/BMSGC.git)

cd BMSGC

### Install Dependencies

Install via pip:

pip install -r requirements.txt

requirements.txt includes:

torch==1.13.1 torchvision==0.14.1 numpy==1.24.3 pandas==2.0.2 matplotlib==3.7.1 

scikit-learn==1.2.2 opencv-python==4.7.0.72 pillow==9.5.0 tqdm==4.65.0 

lime==0.2.0.1 grad-cam==1.4.6 onnx==1.14.0 onnxruntime==1.15.1 seaborn==0.12.2



### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Contact & Citation

Contact

For questions, issues, or collaboration requests, please contact:

-   Project Maintainer: JhuangLab

-   GitHub Issues: [https://github.com/JhuangLab/BMSGC/issues](https://github.com/JhuangLab/BMSGC/issues)


### Acknowledgements

-   We thank our collaborator for providing clinical data.

-   We acknowledge the open-source community for the foundation models and tools used in this project.
