# cc_lung_image_classification
Detect whether a patient has Covid-19, pneumonia, or no illness using x-ray images of their lungs.   

Codecademy Deep Learning Classification Project.

Repository contents:

lung_class.ipynb: Jupyter Notebook containing the script for cleaning, visualizing, exploring, modeling and verification

train data folder, 3 folders 1 for each class
112 images covid
71 images normal & pneumonia

test data folder, 3 folders 1 for each class
27 images Covid
21 images Pneumonia and Normal

each image is 256 x 256 greyscale

weights.hdf5 : weights saved from the ModelCheckpoint callback in keras which holds the weights for the epoch with the lowest cross entropy

ImageDataGenerator folder: Empyt foler made to hold the images after batching and augmenting. Not necessary if not saving images to a folder. 