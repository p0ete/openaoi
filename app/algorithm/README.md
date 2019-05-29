# Python virtual environment

First you need to setup your Python environement.

Create a virtual environment:

> mkvirtualenv NAME_OF_ENV

Install the required packages:

> pip install -r requirements.txt --upgrade

# Copy paste your images

You need to copy the images into the folder: "./data/original/"

# Open Jupyter notebook

To enter the notebook, run the commmand: 

> jupyter notebook 

It will open your browser to http://localhost:8888/ by default.

Then you can open "Preprocess and label images" and follow the instructions in the notebook.

For the moment, only the binary classification on the fiducial gives good results. You can follow the instructions in the "Binary Classification" notebook. The matching algorithm on the fiducials gives a lot of noise. Maybe we could mix both techniques. For the testpoints we clearly, don't have enough data. 

# Acknowledgment

The BBox-Label-Tool is the one from this repository:

https://github.com/puzzledqs/BBox-Label-Tool