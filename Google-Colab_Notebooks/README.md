This Folder contains all the notebooks used to run the experiments. The main structure remains the same, only the hyperparameters were changed.

The hyperparameter changes are as follow (the square bracketes are the files in which the hyper parameters are used upon):

1) Number of Epochs: 1, 10 and 25 [ Devolved-U-Net_Implementation.ipynb, U-Net_Implementation.ipynb, Special-U-Net_Implementation.ipynb ]
2) Learning Rate: 0.1, and 0.0001 [U-Net_Implementation.ipynb, Special-U-Net_Implementation.ipynb]
3) Momentum: 0.9, and 0.9999 [U-Net_Implementation.ipynb, Special-U-Net_Implementation.ipynb]
4) Weight Decay: 1e-2, 1e-4, and 1e-6 [U-Net_Implementation.ipynb, Special-U-Net_Implementation.ipynb]
5) AdaGrad Optimizer [U-Net_Implementation.ipynb, Special-U-Net_Implementation.ipynb]
6) GradScaler: growth_factor=5.0, backoff_factor=0.15 [U-Net_Implementation.ipynb, Special-U-Net_Implementation.ipynb]
7) Criterion: Jaccard Loss [U-Net_Implementation.ipynb, Special-U-Net_Implementation.ipynb]
