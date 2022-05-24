# Indian Sign Language Detection

# How to capture images:
  To capture the images for the training/testing process we will run the Image_capturing.ipynb which will create a folder named data which have test and train folder, each having subfolders named from 0 to 9. The openCV window will save the picture to the proper folder as we press the key for the number. For e.g. in the openCV window if we press '1' then the camera will capture the image and save it in the subfolder named '1'.

# How to Process the captured images:
  To process the images to convert them into viable for training/testing process we will run Image_Pre_Processing.ipynb which will create another folder named data2 which have test and train folder, each having subfolders named from 0 to 9. The notebook will also import the image_processing.py to apply Gaussian Blur filter on the captured images in the data folder and save them correspondingly in appropriate folders in data2. The user needs to change the paths in order to process either test folder or train folder.
  
# How to Train:
  To train a model we give the path of the train folder in data2 to the Training.ipynb and after training we will save the model.
  
# How to Test:
  To test the model we trained and saved, we will run the Testing.ipynb and get the results in the accuracy and can be expanded to obtain a confusion matrix.
  
# How to Predict:
  To predict the model for our use we provide the path of the folder which have all the images to get the predictions.
