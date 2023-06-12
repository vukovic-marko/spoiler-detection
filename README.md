# Spoiler Detection in Book Reviews

🔍 Spoiler Detection in Book Reviews is a project that aims to automatically detect spoilers in book reviews using a Bidirectional Recurrent Neural Network (RNN) based on the Hierarchical Attention Network (HAN) model. The system achieves an accuracy of 78% in identifying potential spoilers.

## Key Features

- Automatically detect spoilers in book reviews.
- Utilizes a Bidirectional RNN with HAN architecture.
- Preprocessing pipeline for handling text data.

## Repository Contents

- 📋 [paper.pdf](https://github.com/vukovic-marko/spoiler-detection/blob/master/paper.pdf): Research paper detailing the methodology, experiments, and findings of the spoiler detection system.
- 📁 [dataset_preprocessing.ipynb](https://github.com/vukovic-marko/spoiler-detection/blob/master/dataset_preprocessing.ipynb): Jupyter Notebook for dataset preprocessing.
- 📁 [model_implementation_and_training.ipynb](https://github.com/vukovic-marko/spoiler-detection/blob/master/model_implementation_and_training.ipynb): Jupyter Notebook for model implementation and training.

## Dataset and GloVe Embedding File

1. Download the dataset from [Dataset Link](https://drive.google.com/uc?id=196W2kDoZXRPjzbTjM6uvTidn6aTpsFnS) and place it in the appropriate directory.

2. Download the GloVe embedding file from [GloVe Embedding Link](http://nlp.stanford.edu/data/glove.6B.zip) and extract the `glove.6B.100d.txt` file to the project directory.

## Required Python Libraries

To run the code, you need to have the following Python libraries installed:

- pandas
- numpy
- nltk
- keras
- matplotlib

## Running the Code

1. Preprocess the dataset:
   - Open the Jupyter Notebook `dataset_preprocessing.ipynb`.
   - Execute the code cells in sequential order to perform dataset preprocessing tasks.

2. Implement and train the model:
   - Open the Jupyter Notebook `model_implementation_and_training.ipynb`.
   - Run the code cells to implement the Bidirectional RNN with HAN model and train it on the preprocessed dataset.

Please refer to the code and comments provided within the Jupyter Notebooks for more detailed instructions.

If you have any questions or suggestions, feel free to reach out. Let's enhance the reading experience by detecting spoilers in book reviews! 📖🚀
