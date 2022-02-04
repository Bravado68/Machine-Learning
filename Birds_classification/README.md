
## Description

 <p align="center">
  <img src="https://storage.googleapis.com/kaggle-datasets-images/534640/978100/13c0e07ffd22fa6876d02514310d4cb8/dataset-card.jpg?t=2020-02-29-23-01-19">
</p>


Data set of 350 bird species.50944 training images, 1750 test images(5 images per species) and 1750 validation images(5 images per species.
All images are 224 X 224 X 3 color images in jpg format. Data set includes a train set, test set and validation set. Each set contains 350 sub directories, one for each bird species. 

The data structure is convenient if you use the Keras ImageDataGenerator.flowfromdirectory to create the train, test and valid data generators. The data set also include a file Bird Species.csv. This cvs file contains three columns. The filepaths column contains the file path to an image file. The labels column contains the class name associated with the image file. The Bird Species.csv file if read in using df= pandas.birdscsv(Bird Species.csv) will create a pandas dataframe which then can be split into traindf, testdf and validdf dataframes to create your own partitioning of the data into train, test and valid data sets.

NOTE: The test and validation images in the data set were hand selected to be the "best" images so your model will probably get the highest accuracy score using those data sets versus creating your own test and validation sets. However the latter case is more accurate in terms of model performance on unseen images.

Images were gather from internet searches by species name. Once the image files for a species was downloaded they were checked for duplicate images using a python duplicate image detector program I developed. All duplicates detected were deleted in order to prevent their being images common between the training, test and validation sets.

## Objective

Create a machine learning classification model with `Tensorflow`
