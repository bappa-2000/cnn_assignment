# Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [Objective](#objective)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Objective
- Use a dataset consisting of 2357 images of malignant and benign oncological diseases of 9 classes, which were formed from the International Skin Imaging Collaboration (ISIC)
- Create a CNN model, which can accurately detect 9 classes present in the dataset.
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~50 epochs
- Explain the findings

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- NumPy - version 1.21.6
- Pandas - version 1.3.5
- PIL - version 7.1.2
- Matplotlib - version 3.4.3
- Tensorflow - version 2.8.2
- Keras - version 2.8.0
- Augmentor - version 0.2.10

## Conclusions
- The 3rd Model built using Augmentor to remove class imbalance looks good.
- Accuracy level of this model is good.
- There is stil some overfitting as the validation loss is higher than the training loss. 
- More epochs and layers can be added while building this model to overcome overfitting

## Acknowledgements
- Reference code taken from Upgrad Learn Portal
- Some Google search 

## Contact
Created by [@bappa-2000] - feel free to contact me!
