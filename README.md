# FastMRI_DataVisualization
This repository is build around FastMRI dataset.

Accelerating Magnetic Resonance Imaging (MRI) by acquiring fewer measurements has the potential to reduce medical costs, minimize stress to patients and make MR imaging possible in applications where it is currently prohibitively slow or expensive.

fastMRI is a collaborative research project from Facebook AI Research (FAIR) and NYU Langone Health to investigate the use of AI to make MRI scans faster. NYU Langone Health has released fully anonymized knee and brain MRI datasets that can be downloaded from the fastMRI dataset page (https://fastmri.med.nyu.edu/). Also required BART: Computational Magnetic Resonance Imaging: https://mrirecon.github.io/bart/ [Download and Installation:] https://mrirecon.github.io/bart/installation.html

# MRI Data Visualization with FastMRI

This repository demonstrates how to visualize MRI data using the [FastMRI](https://github.com/facebookresearch/fastmri) library. FastMRI is an open-source framework developed by Facebook Research for accelerating MRI through deep learning methods.

## Requirements

To use this code, you'll need to have the following dependencies installed:

- Python 3.7 or higher
- `torch`
- `fastmri`
- `h5py`
- `matplotlib`
- `numpy`

You can install the dependencies using the following command:

bash
pip install torch fastmri h5py matplotlib numpy


We encourage to read the following papers for more details:

1. Zbontar, J., Knoll, F., Sriram, A., Murrell, T., Huang, Z., Muckley, M. J., ... & Lui, Y. W. (1811). fastMRI: An open dataset and benchmarks for accelerated MRI. arXiv 2018. arXiv preprint arXiv:1811.08839.
2. Uecker, Martin, et al. "ESPIRiT—an eigenvalue approach to autocalibrating parallel MRI: where SENSE meets GRAPPA." Magnetic resonance in medicine 71.3 (2014): 990-1001.
