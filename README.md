# GaitRDAE
Official Repository of GaitRDAE.
This repository is currently under code reorganization. It is part of an effort to optimize, refactor, and structure the codebase for better maintainability and readability.

## Abstract
Abstract—Deep learning-based gait recognition has achieved great success in various applications. The key to accurate gait recognition lies in considering the unique and diverse behavior patterns in different motion regions, especially when covariates affect visual appearance. However, existing methods typically use predefined regions for temporal modeling, with fixed or equivalent temporal scales assigned to different types of regions, which makes it difficult to model motion regions that change dynamically over time and adapt to their specific patterns. To tackle this problem, we introduce a Region-aware Dynamic Aggregation and Excitation framework (GaitRDAE) that automatically searches for motion regions, assigns adaptive temporal scales and applies corresponding attention. Specifi- cally, the framework includes two core modules: the Region- aware Dynamic Aggregation (RDA) module, which dynamically searches the optimal temporal receptive field for each region, and the Region-aware Dynamic Excitation (RDE) module, which emphasizes the learning of motion regions containing more stable behavior patterns while suppressing attention to static regions that are more susceptible to covariates. Experimental results show that GaitRDAE achieves state-of-the-art performance on several benchmark datasets.

## Getting Started
Please follow our documentation step by step.

## Environment Setup
conda create --name gaitrdae python=3.8
conda activate gaitrdae
pip install tqdm pyyaml tensorboard opencv-python tqdm py7zr tabulate termcolor six
pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
