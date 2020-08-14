# Car_brand_classifier
Transfer learning to recognize car brands of toyota camry, corolla, honda accord, civic, Ford fusion, taurus, f150, Cadillac escalade
For the training set we used 398 images and for validation set 263 images. These were classified into 8 classes.
We transfer learn the parameters trained in ResNet50 https://keras.io/api/applications/resnet/#resnet50-function
As shown in the train/validation loss and train/validation accuracy plots, the NN has high-varience and high-bias problems. 
Applying regularization and using a different architecture might improve the result
