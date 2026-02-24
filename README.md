# xct-segmentation-code

This repository contains the code used for the multi-domain XCT composite segmentation experiments.

## Contents
- `Composite_Segmentation_verison_1.0.ipynb`: main training/evaluation notebook
- `requirements.txt`: minimal Python dependencies

## Setup
Run: `pip install -r requirements.txt`

**Note (PyTorch):** Installing PyTorch depends on your OS/CUDA. If `torch` installation fails, install PyTorch using the official selector and then install the remaining packages.

## Dataset
The dataset is **not included** in this repository.

Dataset DOI/link: https://doi.org/10.5281/zenodo.18751261

Download the dataset ZIP from the link above and set the dataset path inside the notebook (Cell 1).

## Running
Open and run the notebook from top to bottom:
- `Composite_Segmentation_verison_1.0.ipynb`

## License
MIT License. See `LICENSE`.
