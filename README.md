# LungCancerDetection
This repo is for the Qmind lung cancer detection project.

Our team tackled the task of finding cancer-indicating masses and nodules within lung tissue through the NIH ChestX-ray8, a publicly available chest x-ray dataset containing 112,120 clasified images of various images. We tested 3 models, Vgg16, ResNet50, and a AlexNet, and trained them on the 8313 images showing or not showing masses/nodules. You can read up on our findings in [our research paper](https://github.com/JacksonKehoe/LungCancerDetection/blob/main/CUCAI_Lung_Cancer_Paper.pdf).

For our final results, you can find the final models notebooks in the [models](https://github.com/JacksonKehoe/LungCancerDetection/tree/main/models) folder and Jackson's rough notebooks in [previous_notebooks](https://github.com/JacksonKehoe/LungCancerDetection/tree/main/previous_notebooks).

Using the Vgg16, we created a demo for the project where you can visually see the ground truth bounding box (green) and the predicted bounding box (blue) of our project.

Before running these notebooks, ensure that your envionrnment has all the required packages and libraries as it outlines inside notebook. 

NOTE: in order to run the projects yourself, you need to download the [NIH ChestX-ray8 images and .csv files](https://www.kaggle.com/datasets/nih-chest-xrays/data). Due to the size of the models we've trained, we cannot upload them to Github. 

