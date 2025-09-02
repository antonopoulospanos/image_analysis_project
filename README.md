# A7 Image Analysis

This project was to work with classical image processing and data driven regularisation for inverse problems using butterfly images, with additional ML/DL studies on the MNIST dataset

Author: Panos Antonopoulos (University of Cambridge)

## Information

The structure of this repository is as follows:

* The `code` folder which includes the code for the project in Jupyter notebooks. This contains the following files:
    * `module1.ipynb` which is the Jupyter notebook for module 1 of the coursework
    * `module2.ipynb` which is the Jupyter notebook for module 2 of the coursework
    * `module3_ex3.1.ipynb` which is the Jupyter notebook for module 3, exercise 3.1 of the coursework
    * `module3_ex3.2ab.ipynb` which is the Jupyter notebook for module 3, exercise 3.2.a and 3.2.b of the coursework
    * `module3_ex3.2c.ipynb` which is the Jupyter notebook for module 3, exercise 3.2.c of the coursework
    * `unet.py` which is taken from [here](https://github.com/facebookresearch/fastMRI/blob/main/fastmri/models/unet.py): O. Ronneberger, P. Fischer, and Thomas Brox. U-net: Convolutional networks for biomedical image segmentation. In International Conference on Medical image computing and computer-assisted intervention, pages 234–241. Springer, 2015. This is used for module 2 and module 3.

    
* The `requirements.txt` file which contains the Python packages used in this project (specifically for module 1). To use this, please make a new virtual environment and use it to run the command `pip install -r requirements.txt` 


* The `data` folder which includes the unmodified original butterfly images given in the coursework, together with the `background_removed` folder which includes the butterflies with their backgrounds removed and the `collages` folder which includes the collages of butterflies from each group (colour)


* The `report` folder which contains the project report

## Notes

Please make sure the `.pkl` files from [this link](https://drive.google.com/drive/folders/1_q2EYQFPkIqp_-XpIM7-cu50I2dJVrWY) are included in the repository before running module 3, exercise 3.2. Thank you!

A Declaration of Use of Auto-generation Tools:

ChatGPT was used in this project. This tool was used for the following tasks:

* Assisting with debugging code.
* Writing function docstrings.
* Assisting with plotting the collage.
* Assisting with using dictionaries.
* Assisting with plotting figures.
* Assisting with finding the average Euclidean distance between images.
* Assisting with loading image as PyTorch tensor and general PyTorch syntax.
* Assisting with rephrasing wording in the report.
* Assisting with pyiqa syntax.
* Assisting with grabcut.
* Assisting with shuffling data before creating PyTorch dataloaders.
* Making bibtex citations for websites.