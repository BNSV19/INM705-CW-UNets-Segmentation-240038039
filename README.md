# INM705-CW-UNets-Segmentation-240038039
This Repository mainly focuses on creating a modified version of U Network and checking if this new architecture works with segmentation problem.

We will be mainly utilizing CNN family of models (Primarily U-nets in the Encoder Decoder Configuration) to solve the problem of Segmentation.

# Note: The different ipynb files each contain different architectures or contain major hyperparameter improvements.

# How to replicate the results
1a) Navigate to Model-Saves, open the drive link, download the respective model and their corresponding google colab notebook, and finally load the models and weights using torch.load()

or

1b) Navigate directly to the colab notebook, then run the respective notebook on google colab, and get the results and the saved models (skip login for wandb and google drive as per requirement)

2) Use the transfered/trained models to predict newer samples.


# Viewing the sample predictions

Navigate to the Sample-Pred_Images folders, and open the required file. It will contain the raw images for the different experiments run

# Viewing all experiments via wandb

Navigate to Wandb-tracking folder, and open the csv file to see all experiments run and their respective values tracked.

Note: Some fields are empty due to not properly setting up wandb when running those experiments, but their respective log files have the information.
