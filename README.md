
---

### **Actual Rendered Output:**

# Seismic Data Denoising Using Vision Transformer

## Overview
This repository contains a Jupyter Notebook that implements a seismic data denoising technique using a **Vision Transformer (ViT)**. It leverages **machine learning** and **deep learning** frameworks to effectively remove noise from seismic signals, improving data quality for further geophysical analysis.

## Features
- Utilizes **Vision Transformer (ViT)** for seismic data denoising.
- Supports **GPU acceleration** for faster training and inference.
- Implements **machine learning** and **deep learning** techniques using TensorFlow.
- Includes **visualization tools** for assessing denoising performance.
- Supports **data preprocessing, training, evaluation, and model saving/loading**.

## Dependencies
Ensure you have the following libraries installed before running the notebook:

- Python (>= 3.7)
- TensorFlow
- scikit-learn
- NumPy
- Matplotlib
- Pickle

Install the required dependencies using:

```sh
pip install tensorflow scikit-learn numpy matplotlib pickle
```


## GPU Support
This notebook is optimized for **GPU usage**. Ensure you have the proper **CUDA** and **cuDNN** versions installed along with TensorFlow to utilize **GPU acceleration**.

## Usage
### Clone the Repository
```sh
git clone https://github.com/your-username/seismic-denoising-vit.git
cd seismic-denoising-vit
```

## Prepare the Data
Ensure your seismic dataset is correctly formatted and loaded Look at the codebase to know  appropriate shape of seismic section image to reshape your own seismic section data and Modify padding accordingly.
For reasons, Data folder used for our codebase is not provided. Do look into `Data Loader` section of notebook to know more about how Data is organized.

## Run the Notebook
Execute all cells to train and evaluate the model.

## Evaluate Results
Visualize the denoised seismic data and compare it with the noisy input.

## Save/Load Model
Use provided functions to save and load trained models.

## Contributing
Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request with your improvements.

## Contact
For queries, contact `simlab120@gmail.com`.


