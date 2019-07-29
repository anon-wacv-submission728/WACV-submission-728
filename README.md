# SemiSupervised way for segmenting using CycleGANs

The repository contains the code used to train and validate the model architecture and training procedure specified in the WACV submission **PaperID 728**.

For the training and validation we have used VOC, Cityscapes and ACDC dataset.

The structure of the various files is as follows:
1. `model.py` : The training procedure is included here along with tensorboard visualization for viewing training curves
2. `main.py` : The specifications of various hyperparameters and dataset specifications
3. `testing.py` : The testing code on the testing partition of the 3 datasets
4. `validation.py` : The validation code for all the 3 datasets
5. `arch/` : Directory containing architecture for the models used
5. `data/` : Directory that will contain the data for all 3 datasets
6. `data_utils/` : Directory containing dataloaders and specific transformations for all 3 datasets
