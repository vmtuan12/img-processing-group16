Group 16 Mid-term project - Image processing course
==============

# Contributors
- **Vu Minh Tuan**: Pipeline construction (from the beginning to Torch DataLoader), Data analysis, Data pre-processing, Model implementation (Simple convolution)
- **Chu Ngoc Vuong**: Pipeline construction (Model training process), Model researching, Model implementation (Simple convolution, Inception, Xception, ViT, Ensemble), Inference construction
- **Le Viet Viet Linh**: Data pre-processing, Data augmentation, Model researching, Model implementation (Simple convolution, Residual Network)
- **Pham Duc Trung**: Data pre-processing, Model researching, Model implementation (Alexnet, EfficientNet), Inference pipeline construction

**_Note:_** _Model researching_ involves searching for and identifying appropriate models and approaches through research papers, the internet, and other sources.

# Goal
This project aims to explore the application of deep learning techniques, specifically convolutional neural networks (CNNs), to classify Sino-nom characters. CNNs are well-suited for image recognition tasks due to their ability to automatically learn and extract hierarchical features from raw pixel data. By leveraging CNNs, we aim to create a model that can accurately distinguish between different Sino-nom characters based on their handwritten representations.

The primary objectives of this project are:
- To preprocess a given dataset of handwritten Chinese characters, which includes both high quality and low quality images.
- To design and train multiplt deep-learing model capable of classifying these characters.
- To evaluate the performance of the model.
- To ensemble all the top model for the final result.

# Installation
## Structure of the repository

├── data_aug  # folder containing data augmentation scripts (possibly)\
├── image_processing  # folder containing image processing scripts (possibly)\
├── model  # folder containing the main model code\
├── README.md  # main project readme file\
└── requirements.txt  # file containing required python packages\
└── Final-report  #Report of our method and result\

## Setup
**The traing and iference notebook is recommended to be run on Google Colab, with all processes automated for ease of use. **

**If you are running locally:**

1. Install all required dependencies:
```
pip install -r requirements.txt
```
2. Update the dataset directory path in the relevant script:
```
local_dir = 'your path'
```

4. Optional: Change the model configuration 
```
- Model name
- Model parameters (e.g., learning rate, epochs, etc.).
- Checkpoint path.
```

# Result

The best results from the models we used are shown in the table below.

| Method | Validation Accuracy (%) |
|---|---|
| M6 | 79.8 |
| M7 | 80.6 |
| M7X | 81.6 |
| AlexNet | 70.2 |
| ResNet18 | 88.5 |
| EfficientNet B0 | 91.0 |
| EfficientNet B1 | 92.4 |
| Inception V3 | 87.5 |
| Xception | 88.6 |
| Vision Transform Tiny | 69.1 |
| **4 Top Model Ensemble** | **93.6** |

**For a detailed explanation of each model and the intuition behind their design, please refer to the final report.**
