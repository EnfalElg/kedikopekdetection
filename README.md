# Cat vs Dog Image Classifier

This project is a deep learning-based image classifier that distinguishes between images of cats and dogs. The model was built and trained using TensorFlow and Keras in the Google Colab environment. The dataset used is the "Dogs vs Cats" dataset from Kaggle.

## Project Overview

- Dataset: [Dogs vs Cats - Kaggle](https://www.kaggle.com/c/dogs-vs-cats)
- Framework: TensorFlow / Keras
- Model Type: Convolutional Neural Network (CNN)
- Goal: Predict whether an input image contains a cat or a dog

## Google Colab Notebook

You can view and run the full training notebook on Google Colab using the link below:

https://colab.research.google.com/github/EnfalElg/kedikopekdetection/blob/main/kediköpek.ipynb

The notebook contains the full data preprocessing, model training, evaluation, and prediction workflow.

## Steps Performed in the Notebook

1. Dataset download using Kaggle API
2. Data extraction and organization into training and validation folders
3. Image preprocessing and resizing
4. CNN model creation using Keras
5. Model training and validation
6. Final predictions on new images


## Requirements

This notebook was designed to run in Google Colab.  
To run it locally, you may need to install the following packages:

```bash
pip install tensorflow matplotlib numpy kaggle
```

Additionally, make sure to place your `kaggle.json` API key file in the correct directory (`~/.kaggle/` or the working directory).

## Important Notes

- The uploaded notebook does not contain any personal credentials or sensitive information.
- Please use your own Kaggle API key (`kaggle.json`) to access the dataset.
- Before sharing your own notebooks, make sure to clear outputs and remove sensitive data.

## License

This project is licensed under the MIT License.
