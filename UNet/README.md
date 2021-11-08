This model is trained on TGS Salt segmentation dataset. The dataset is available at kaggle (https://www.kaggle.com/c/tgs-salt-identification-challenge).

The loss function is BCEWithLogitsLoss(). 

Will be implementing IOU metric(near future).

The below image is when the depth of the model is 3 (3, 16, 32, 64).
>![This is an image](https://github.com/Teja1631/DeepLearning/blob/main/UNet/output/plot.png)

The below image is when the depth of the model is 4 (3, 16, 32, 64, 128).
>![This is an Image](https://github.com/Teja1631/DeepLearning/blob/main/UNet/output/plot_2.png)
