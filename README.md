# CS 590 Computational Biology Seminar Final Project: PLM Embeddings
## cs590-comp-bio-protein-language-model-project

This project seeks to understand how two key biophysical properties—secondary structure and disorder—are encoded in the embeddings of protein language models, with ESM-2 used for this study. This repo contains all necessary code and data to reproduce the results of this project.

There are n files contained in this repo in addition to this readme, as follows:

### 1. protein_design_final_project.ipynb: project code and data
All code written for this project is included in this notebook. Given that the dataset used in this project came from HuggingFace (https://huggingface.co/datasets/proteinea/secondary_structure_prediction), that dataset is included directly in the notebook as well. A user seeking to reproduce the results will have to get their own HuggingFace token/API key in order for the dataset to be succesfully loaded.

### 2. report.pdf: project report
A full report of the project is included in this PDF.

### 3-n. Folder: Report LaTeX files
All files (main.tex, images, bibliography, etc.) needed to generate the report PDF via LaTeX are included in this folder

## Note on compute:

While using a CPU will work to run this notebook, it should run much faster on GPU. The most compute-intensive step of this code is embedding extraction, which takes approximately 1 minute and 22 seconds for 3000 samples using a T4 GPU. By contrast, it takes approximately _____ for 3000 samples using CPU.
