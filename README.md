# detection-distracted-drivers
detection distracted drivers using CNN

TRAINING

to train the model, you need to add the "data" folder to the directory where the file "main.ipynb" is located.

you can download the folder "data" from the link - https://drive.google.com/open?id=19UaZcx5sxE2qF58Ud66a4WYM8vdsvQLf.

you need to add the "saved_models" folder to the directory where the file "main.ipynb" is located.

then run the code in the file "main.ipynb"

For training we use a ready-made model ResNet50 with weights="imagenet"

you need to add the "saved_models" folder to the directory where the file "main.ipynb" is located.

After each epoch, the architecture of the model and its weight are saved in a folder "saved_models" 

PREDICT

you can use a model with an accuracy of 0.944 to get the prediction

you need to download the folder "saved_models" and paste it into the root directory 

download link - https://drive.google.com/open?id=1qqjo8LAQFirymNtcGGIGGW4GDfrQNiPI

to get the prediction, add an image in folder - 'data/test_min/1' and run the code in the file "predict.ipynb"
