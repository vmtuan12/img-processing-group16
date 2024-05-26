Group 16 Mid-term project - Image processing course
==============

# Contributors
- **Vu Minh Tuan**: Pipeline construction (from the beginning to Torch DataLoader), Data analysis, Data pre-processing, Model implementation (Simple convolution)
- **Chu Ngoc Vuong**: Pipeline construction (Model training process), Model researching, Model implementation (Simple convolution, Inception, Xception, ViT, Ensemble)
- **Le Viet Viet Linh**: Data pre-processing, Data augmentation, Model researching, Model implementation (Simple convolution, Residual Network)
- **Pham Duc Trung**: Data pre-processing, Model researching, Model implementation (Alexnet, EfficientNet), Inference pipeline construction

**_Note:_** _Model researching_ involves searching for and identifying appropriate models and approaches through research papers, the internet, and other sources.

# Goal
This project aims to explore the application of deep learning techniques, specifically convolutional neural networks (CNNs), to classify handwritten Chinese characters. CNNs are well-suited for image recognition tasks due to their ability to automatically learn and extract hierarchical features from raw pixel data. By leveraging CNNs, we aim to create a model that can accurately distinguish between different Chinese characters based on their handwritten representations.

The primary objectives of this project are:
- To preprocess a given dataset of handwritten Chinese characters, which includes both high quality and low quality images.
- To design and train a CNN model capable of classifying these characters.
- To evaluate the performance of the model.

# Installation
## Structure of the repository

├── data_aug  # folder containing data augmentation scripts (possibly)\
├── image_processing  # folder containing image processing scripts (possibly)\
├── model  # folder containing the main model code\
   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ├── linh  # folder containing linh's model\
   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ├── trung  # folder containing trung's model\
   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ├── tuan  # folder containing tuan's model\
   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; └── vuong  # folder containing vuong's model\
├── README.md  # main project readme file\
└── requirements.txt  # file containing required python packages\

## Setup
Firstly, install all the required dependencies

```
pip install -r requirements.txt
```


# Result

# Final report
The report has been pushed to this repository.
