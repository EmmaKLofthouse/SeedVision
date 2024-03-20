# SeedVision

SeedVision is a repository dedicated to identifying different vegetables using neural networks. This project utilizes deep learning techniques to classify various types of vegetables from images.

# Dataset

The dataset used in this project is collected from Google Images, consisting of images of various seeds. Currently, the model is trained on 14 classes: Almond, Apple, Avocado, Brussel Sprout, Carrot, Jackfruit, Lemon, Lychee, Mango, Olive, Poppy, Pumpkin, Sunflower, Tomato. More classes will be added soon to enhance the model's versatility and applicability.

## Scripts

**sort_raw_files.py**: This Python script is used to sort and clean raw images collected from Google Images. It helps organize and preprocess the dataset before feeding it into the neural network models.
    
## Notebooks

**transfer_inception.ipynb**: This notebook showcases the use of transfer learning with the InceptionV3 model for vegetable classification. 

**SeedVision.ipynb**: Tutorial on how to use the trained models to classify your own images.

# Example

Below are example results showing images of seeds along with their true and predicted categories:

![Untitled](https://github.com/EmmaKLofthouse/SeedVision/assets/18194748/17ef7e04-eac3-4c71-a28e-9aa37a4fef4c)

# Contributing

Contributions to SeedVision are very welcome! If you have any ideas, bug fixes, or enhancements, feel free to open an issue or submit a pull request.
