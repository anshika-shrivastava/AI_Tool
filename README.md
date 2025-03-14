# AI_Tool

## How to start the tool locally
https://github.com/anshika-shrivastava/AI_Tool.git  
cd AI_Tool  
Copy the AITool.pynb file over to collab  
Run the cell


## Aim
This repository demonstrates a solution for an AI internship assignment where we integrate a product image (a carpet) seamlessly into AI-generated realistic interior image.

## Overview

This project uses **free and open-source libraries and models** to:
1. **Preprocess Product Images:** Remove white/near-white backgrounds from product photos using OpenCV.
2. **Generate Interior Images:** Used Stable Diffusion to generate high-quality interior images.
3. **Composite Images:** Merge the preprocessed product (carpet) onto the generated interior images at a specified position and scale.

## Files

- `AITool.ipynb`: Main Python script that performs background removal and compositing.
- `README.md`: This file.

## Requirements

### Software & Libraries

- **Python 3.7+**
- [OpenCV-Python](https://pypi.org/project/opencv-python/)
- [Pillow](https://pypi.org/project/Pillow/)
- [PyTorch](https://pytorch.org/) & [torchvision](https://pypi.org/project/torchvision/)
- [diffusers](https://github.com/huggingface/diffusers)
- [transformers](https://pypi.org/project/transformers/)
- [rembg](https://github.com/danielgatis/rembg)
- [onnxruntime](https://pypi.org/project/onnxruntime/)
- [Segment Anything](https://github.com/facebookresearch/segment-anything)
You can install the dependencies with:

```bash
pip install opencv-python pillow torch torchvision diffusers transformers rembg onnxruntime
pip install git+https://github.com/facebookresearch/segment-anything.git
```
### Sam model - https://drive.google.com/file/d/10tfHvQ3ZEub-DcCIUaWFn7IjHgctqMry/view?usp=drive_link
### Preprocessed product image - https://drive.google.com/file/d/1IcYhM5oCWkI3HN6Sql1O54vd_-Q6qnnp/view?usp=drive_link
### Final Image - https://drive.google.com/file/d/1-y5BAf-vjRwGW5UrKepYv14g29cN_0Lm/view?usp=sharing
### Sample Result Image:  
![Screenshot 2025-03-14 232554](https://github.com/user-attachments/assets/eaa633c1-8bfe-4035-bfaa-c7124ef97d46)
