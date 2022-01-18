# EuroSAT-Image-Classification-with-Wide-and-Deep-Learning
Image Classification, Object Detection Project with Wide and Deep Learning for Remote Sensin Field on EuroSAT Satellite Images
Hi, welcome to my research of wide and deep learning :)

I would like to special thanks to my professeurs and supporters.

Beril Sirmacek b.sirmacek@saxion.nl and Cem Unsalan cem.unsalan@marmara.edu.tr

![EuroSAT Sample Images](https://github.com/mcagriaksoy/EuroSAT-Image-Classification-with-Wide-and-Deep-Learning/blob/main/eurosat_overview.jpg)

# Dataset Preparation 
This will connect to my drive and copy the contents from my related drive path.
The dataset is gathered from Kaggle: https://www.kaggle.com/apollo2506/eurosat-dataset


> This dataset is being used for classifying the use of land in geospatial images. The end goal for the classification is that the top 2 uses of land in an image are given as output to the user.

> This dataset contains images belonging to the EuroSat dataset. It contains RGB images collected from the Sentinel Dataset.


It has 10 classes that represents the field of:

    AnnualCrop
    Forest
    HerbaceousVegatation
    Highway
    Industrial
    Pasture
    PermanentCrop
    Residential
    River
    SeaLake

Each image is 64x64 pixels with a Ground Sampling Distance of 10m. They were all collected from the Sentinel-2 satellite. But we are resized them to 32x32 to less training time requirements.

# Data Gathering
In this step, the data will be gathered and processed (making ready) for the cnn model feeding.
Our dataset has the json file that describes the classes of each image and with this info we classify them on. We also resize whole dataset as 32x32 which is minimum acceptable resolution for many famous models.

will be updated...

2021 - Created By Mehmet Çağrı Aksoy (Software Engineer)
