# DSA2000
This is a project to develop segmentation models to separate radio interference from radio imaging readings. This project contains the notebooks of the models and explains how to use them. However, the primary repository is on Google Drive and is linked below.
## Tutorial
Most of this project was done in Google Colab, so the files under "models" are notebooks that should be opened in Google Colab. In order for the necessary pathways to be set up, users should join the shared [Google Drive group](https://drive.google.com/drive/folders/1HH3Apa7B-0AzHfAjen9mQODh37urue2a?usp=sharing).

Within each notebook, there are multiple code blocks that should be run in succession in order for imports, data, model definitions, etc. to be set up. These contain titles on each section, so it should be clear what each section is doing when run. After the intial set up blocks are run, there are further code blocks that are used for loading past models or for training new models.

The sections labeled "Load Model" are used for loading past models. The paths in these code blocks can be modified to load different models. Similarly, the paths in the sections "Train New Model" can be changed to save new models.

Finally, there are further sections that can be used to visualize model functionality. Some such as "Visualize Trained Model" run the model on specific input images and plot the results as frequency vs. time plots. "Plot Loss Curves" plots the saved losses from training, and different training sessions can be loaded by changing the csv paths.
