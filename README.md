# CK-SsDGLVM: Causal Knowledge-Assisted Semi-Supervised Dynamical Generative Latent Variable Model
This repository contains the code and supplementary materials for the paper "A Causal Knowledge-Assisted Semi-Supervised Dynamical Generative Latent Variable Model for Industrial Quality Index Prediction", published in IEEE Transactions on Systems, Man, and Cybernetics: Systems.
**Overview**
Generative latent variable models (GLVMs) are widely used in industrial soft sensing. However, existing Dynamical GLVMs (DGLVMs) often focus on temporal correlations while disregarding causal relationships between variables, thereby compromising generalization performance.
CK-SsDGLVM is a novel framework that integrates physical causal knowledge (specifically regarding intervention variables) into a semi-supervised DGLVM. It utilizes an Expectation-Maximization (EM) algorithm for parameter learning and demonstrates superior accuracy and interpretability compared to benchmark models like DPLS, LSTM, Transformer, and standard SsLDS.
**Key Features**
Causal Integration: Explicitly models the causal influence of intervention variables (inputs of energy/material) on latent states.
Semi-Supervised Learning: Effectively handles scenarios with scarce labeled quality data using an EM-based training algorithm.
Industrial Application: Validated on both artificial numerical cases and a real-world Low-Temperature Reaction Unit (LTRU) in an ammonia synthesis plant.
**Citation**
If you use this code or the associated data in your research, please cite the following paper:
@article{han2026causal,
  author={Han, Wenxue and Tian, Ze and Shao, Weiming and Chen, Junghui},
  journal={IEEE Transactions on Systems, Man, and Cybernetics: Systems}, 
  title={A Causal Knowledge-Assisted Semi-Supervised Dynamical Generative Latent Variable Model for Industrial Quality Index Prediction}, 
  year={2026},
  volume={56},
  number={3},
  pages={2021-2035},
  doi={10.1109/TSMC.2025.3648195}
}
Full Reference:
W. Han, Z. Tian, W. Shao, and J. Chen, "A Causal Knowledge-Assisted Semi-Supervised Dynamical Generative Latent Variable Model for Industrial Quality Index Prediction," in IEEE Transactions on Systems, Man, and Cybernetics: Systems, vol. 56, no. 3, pp. 2021-2035, March 2026, doi: 10.1109/TSMC.2025.3648195.
**Data Availability**
The datasets used in this study (including the industrial data from the ammonia synthesis plant) are not directly included in this repository due to privacy and proprietary constraints.
To request access to the data: Please contact the corresponding author directly.
Usage Requirement: If you obtain the data, you must formally cite the paper mentioned above in any resulting publications or reports.
Corresponding Author Contact:
Weiming Shao
College of New Energy, China University of Petroleum (East China), Qingdao, China.
📧 Email: shaoweiming@upc.edu.cn
For questions regarding the code or methodology, please contact:
Wenxue Han: hanwenxue@s.upc.edu.cn
Weiming Shao: shaoweiming@upc.edu.cn
