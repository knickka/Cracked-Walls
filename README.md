# Cracked-Walls
ML model to classify cracked concrete wall

##Crack_detection
Crack_detection file contains Ml model to detect cracks on concrete wall. The model is based on pytorch's pre trained model resnet18.
images are 3 channel and 224*244
Total 30000 train images trained with 100 per batch and 10000 validation image with 100 per batch
train time about 2 hours
accuracy : .9976
finally the whole model is saved for later use
#Classifier
Classifer first loads the previously saved model
classify function first takes an image path and pre-proceeses it for the model
it then runs the image through the model and saves the result
and finally plots the image with predicted class

model is set to evaluation mode before calling the function 
