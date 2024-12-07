# Projects Repository

## Image Analysis

### Overview
These projects are actively being developed to process whole slide images (WSI) using the StarDist model for nuclei segmentation and to classify breast cancer histopathological images. The primary focus is on binary classification of breast cancer histopathological images into benign and malignant categories using convolutional neural networks (CNNs). As these projects are ongoing, additional functionalities and improvements may be integrated over time.


## Prerequisites
Ensure Python 3 is installed on your system. Python can be downloaded from the official Python website.

### Installation
Create and activate a virtual environment.

Install dependencies:
```
pip install numpy pandas scikit-image scikit-learn stardist openslide-python joblib matplotlib
```

### Usage for Stardist 
1. Segment nuclei using the StarDist model.
2. Optionally visualize segmented nuclei.

### Breast Cancer Histopathological Image Classification Overview
The breastcancerclassification.py script performs binary classification of breast cancer histopathological images into benign and malignant categories using convolutional neural networks (CNNs). Before running the script, please ensure that you have the dataset prepared in the following format:

```dataset_dir/
├── benign/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── malignant/
    ├── image1.jpg
    ├── image2.jpg
    └── ...
```


### Usage for Breast Cancer Histopathological Image Classification

1. **Dataset Preparation**: Obtain a dataset of breast cancer histopathological images. Organize the dataset into subdirectories representing the different classes (benign and malignant).

2. **Running the Script**: Set the `dataset_dir` variable in the script to the path of the dataset directory. Run the script using Python. It will train the CNN model and evaluate its performance using ROC curves and AUC.

3. **Interpreting Results**: After running the script, analyze the generated ROC curve and AUC score. These metrics provide insights into the model's ability to distinguish between benign and malignant tissue samples. A higher AUC score indicates better performance.



## Code to Codons

### Overview
A Streamlit web application that simulates the conversion of text to DNA, applies mutations, and translates the DNA through RNA into protein sequences.

### Features
- Convert text to DNA sequence.
- Mutate DNA and transcribe into RNA.
- Translate RNA to protein and highlight stop codons.

## Prerequisites
Before you begin, ensure you have Python installed on your system. You can download Python from [python.org](https://www.python.org/downloads/). This project assumes you are using Python Python 3.11.7.

### Installation
1. Clone the repo and navigate into the specific project directory.
2. Create a virtual environment and install dependencies.
3. Run the app with `streamlit run app.py`.

### Usage
Input text to convert and mutate into DNA, view the RNA transcription, and the resulting protein sequence with highlighted stop codons.

### Modules
Includes modules for DNA conversion, mutation, RNA transcription, and protein translation.

## Random Folder

The "random" folder within this repository contains a variety of projects at different stages of development. Many of these projects are works in progress, undergoing testing, refinement, or expansion. This folder serves as a creative sandbox, reflecting my ongoing exploration and experimentation with new ideas and technologies. While some projects in this folder may not be fully functional or documented, they offer a glimpse into my interests.

## Just_For_Fun

This directory contains casual and experimental scripts created for entertainment and exploration.