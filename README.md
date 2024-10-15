Album Cover Generator
Description
This project is an AI-powered Album Cover Generator that uses a combination of Convolutional Neural Networks (CNNs) for genre classification and Generative Adversarial Networks (GANs) for album cover generation. It takes an input song, predicts its genre, and generates unique album cover art based on that genre.
Features

Genre classification of input songs using CNN
Album cover generation using GAN
Support for multiple genres: rock, pop, classical, hiphop, country, latin, edm_dance, jazz
Option to use pre-trained models or create new ones
Interactive user interface for genre confirmation and selection

Installation

Clone this repository
Install the required dependencies:
Copypip install opendatasets librosa numpy matplotlib torch torchvision tqdm tensorflow sklearn pillow ipywidgets

Mount your Google Drive to access saved models (if using Google Colab)

Usage

Run the cells in the provided Jupyter notebook in sequence:

Install and import necessary libraries
Set up genre classification model
Set up album cover generation model
Input a song and get the predicted genre
Confirm or update the selected genre
Generate album cover art


Upload a song when prompted
Confirm or change the predicted genre using the dropdown menu
View and download the generated album covers

Model Training

The genre classification model is trained on a dataset of audio spectrograms
The album cover generation model (GAN) is trained on a dataset of existing album covers for each genre

Pre-trained Models

Pre-trained models can be found on GitHub (link to be added)
Place these models in the root directory of your Google Drive to use them

Creating New Models

If pre-trained models are not available, the system will automatically create new ones
Note: Accessing the database for new model creation requires a Kaggle username and key

Output

The system generates multiple album covers and displays the top 5 based on the discriminator's score
Generated images can be downloaded from the Colab file section

Notes

This project uses Google Colab for execution
Ensure you have necessary permissions and access to required datasets
