# Source code for: "Exposing Fake Images Forensic Similarity Graphs" 
by Owen Mayer and Matthew C. Stamm  
Deparment of Electrical and Computer Engineering  
Drexel University - Philadelphia, PA, USA

Visit the [project webpage](http://omayer.gitlab.io/forensicgraph/)

The [paper](https://ieeexplore.ieee.org/abstract/document/9113265) is available through the IEEE Journal of Selected Topics in Signal Processing 

The code in this repository will:
1. provide capability to run the algorithms described in the paper
2. reproduce the results in the paper

Note 9/10/2020: This repo is currently in development and should be finalized by 9/18/2020

## Getting Started

Please follow the examples in jupyter notebooks in the main directory for how to use this code.
- *0_compute_visualize_similarity_graph* shows how to compute the forensic similarity graphs and how to reproduce Figure 1 from the paper
- *1_forgery_detection* shows how to compute forgery detection scores
- *2_forgery_localization* shows how to compute forgery localization prediction masks
- *3_compute_and_save_simgraph_for_benchmark_DBs* computes the forensic graphs for the three tampering datasets and saves to disk, to be used in subsequent notebooks
- Not yet available: *4_benchmark_forgery_detection* reproduces forgery detection results 
- Not yet available: *5_benchmark_forgery_localization* reproduces forgery localization results 

## Requirements
- Python 3
- tensorflow 1.15 (gpu version recommended)
- pillow
- seaborn
- tqdm
- python-igraph (available from conda-forge)
- jupyter-notebook (for running examples)

## Cite this code
If you are using this code for academic research, please cite this paper:

Mayer, Owen, and Matthew C. Stamm. "Exposing Fake Images with Forensic Similarity Graphs." *IEEE Journal of Selected Topics in Signal Processing* (2020).

bibtex:
```
@ARTICLE{mayer2020forensicgraphs,
  author={O. {Mayer} and M. C. {Stamm}},
  journal={IEEE Journal of Selected Topics in Signal Processing}, 
  title={Exposing Fake Images With Forensic Similarity Graphs}, 
  year={2020},
  volume={14},
  number={5},
  pages={1049-1064},}
```