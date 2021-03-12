# PokéPredict
A collection of models related to various aspects of Pokémon.
* [Creates](#generate-pokmon) new Pokémon from images of pre-existing in PyTorch by training a deep convolutional generative adversarial network (DCGAN)
* [Predicts](#image-classification) Pokémon’s type from input image using multi-label classification in TensorFlow and Keras with a convolutional neural network (CNN)
* [Classifies](#legendary-prediction) legendary status of Pokémon based on its other statistics

## Generate Pokémon
Placeholder
![output1](images/generate/chosen.png)
![generate](images/generate/generated.png)

## Image Classification
Various CNNs classifying the type of Pokémon based off of an image. 
![output1](images/types/predictions.png)

## Legendary Prediction
A collection of models classifying the status (legendary, sub-legendary, mythical, normal) of Pokémon based off of stats like attack, defense, type, egg cycles, etc. 
Our most successful models are Random Forests achieving accuracies of ~99%, with logistic regression, neural networks, and SVMs being other models that achieved 95%+ accuracy. 


## Getting Started
How to run the application

1. Clone the repository.
2. Edit and rerun the Jupyter Notebooks as desired.

## Data Sources
* [Complete Pokemon Dataset](https://www.kaggle.com/mariotormo/complete-pokemon-dataset-updated-090420)
* [Pokemon Image Dataset](https://www.kaggle.com/vishalsubbiah/pokemon-images-and-types)
* [Pokemon Images](https://www.kaggle.com/dollarakshay/pokemon-images)
* [7,000 Labeled Pokemon](https://www.kaggle.com/lantian773030/pokemonclassification)

## Built With
* [PyTorch](https://pytorch.org/) - Deep Learning
* [TensorFlow](https://www.tensorflow.org/) - Deep Learning

## License
This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.
