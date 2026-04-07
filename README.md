# INM705-CW-UNets-Segmentation-240038039
This Repository mainly focuses on creating a modified version of U Network and checking if this new architecture works with segmentation problem.

# Note: The different ipynb files each contain different architectures or contain major hyperparameter improvements.

# How to replicate the results
1a) Navigate to Model-Saves, open the drive link, download the respective model and their corresponding google colab notebook, and finally load the models and weights using torch.load()

or

1b) Navigate directly to the colab notebook, then run the respective notebook on google colab, and get the results and the saved models (skip login for wandb and google drive as per requirement)

2) Use the transfered/trained models to predict newer samples.


# Viewing the sample predictions

Navigate to the Sample-Pred_Images folders, and open the required file. It will contain the raw images for the different experiments run
