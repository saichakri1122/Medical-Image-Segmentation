# Medical Image Segmentation using U-Net and MedSAM

## Overview
This project focuses on medical image segmentation of CT scan images using deep learning techniques. It combines U-Net for initial segmentation and MedSAM for prompt-based refinement.

## Objective
The goal is to identify and segment regions of interest (such as lung structures or abnormalities) from CT images to assist in medical analysis.

## Methodology
1. Preprocessed CT scan images
2. Applied U-Net model for initial segmentation
3. Used MedSAM for prompt-based segmentation refinement
4. Visualized and compared outputs

## Technologies Used
- Python
- PyTorch
- NumPy
- Matplotlib
- MedSAM


## Results

### Input Image
![Input](input_images/sample1.png)

### U-Net Output
![U-Net Output](output_images/unet_output.png)

### MedSAM Output
![MedSAM Output](output_images/medsam_output.png)

## Observations
The model demonstrates initial segmentation capability by identifying regions of interest. While results are not perfect, they show the effectiveness of combining deep learning with prompt-based segmentation techniques.

## Limitations
- Limited training data
- Model requires further tuning for higher accuracy

## Future Improvements
- Improve model training with larger dataset
- Enhance segmentation accuracy
- Deploy model for real-time usage

## How to Run
1. Install required libraries:
   pip install -r requirements.txt

2. Run the inference script:
   python inference.py
