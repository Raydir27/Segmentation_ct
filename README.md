# Segmentation_ct

Here's a GitHub README template for your project:

---

# CT Scan Image Segmentation with Transformers

This repository contains the code for a segmentation model for CT scan images using Transformer-based architectures. The model has been adapted and implemented with reference to the work in the [Medical Segmentation Transformer](https://github.com/OlgaOlmi/medical_seg_transformer/tree/main) repository by OlgaOlmi.

## Overview

Medical image segmentation is a crucial task in the analysis of CT scan images. This project focuses on implementing a segmentation model for detecting regions of interest in CT scans using advanced transformer architectures. The provided `.ipynb` notebook includes the full pipeline for data preprocessing, model architecture, training, and evaluation.

## Repository Structure

- `CT_Scan_Segmentation_SWinV2.ipynb`: Jupyter notebook containing the code for the segmentation model.
- `requirements.txt`: A list of dependencies required to run the notebook.
  
## Pretrained Model

You can download the pretrained model used in this project from the following link:

[**Download Pretrained Model**](#)  
[Trained_Model_link](https://drive.google.com/drive/folders/1mWPQwZf68XFQeSf7Zn-X6cvg-8S1s0W-?usp=sharing)

## Instructions

### 1. Install Dependencies

To run the code, first, ensure that all dependencies are installed. You can install the required packages by running:

```bash
pip install -r requirements.txt
```

### 2. Running the Notebook

Once dependencies are installed, you can open and run the Jupyter notebook:

```bash
jupyter notebook CT_Scan_Segmentation.ipynb
```

The notebook contains code for:
- Loading and preprocessing CT scan data.
- Defining the segmentation model using transformers.
- Training the model on the dataset.
- Evaluating and visualizing the segmentation results.

### 3. Loading the Pretrained Model

Once you have downloaded the pretrained model, load it into the notebook by replacing the model loading code in the appropriate cell:

```python
# Example for loading the pretrained model
model.load_state_dict(torch.load('path_to_saved_model.pth'))
```

### Acknowledgements

This implementation is inspired by and based on the work from the [Medical Segmentation Transformer](https://github.com/OlgaOlmi/medical_seg_transformer/tree/main) repository. Special thanks to OlgaOlmi for their open-source contributions to medical image segmentation.

---

Feel free to add more sections, details, or personalize it further! Don't forget to replace the placeholder with the actual Google Drive link to your pretrained model.
