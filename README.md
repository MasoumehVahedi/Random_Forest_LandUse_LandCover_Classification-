# Random_Forest_LandUse_LandCover_Classification-

In this project I classified Land use/ Land cover of an area using machine learning algorithm (random forest model) with python. The random forest algorithm was implemented to classify the landsat images into 4 classes, including: 
1- Water 2- Vegetation 3- Urban 4- Wetland 

The following phases has been implemented for land use/land cover classification: 
1- The first phase, I separated Training and Test data in QGIS and save them as shapefile allocated id for each class_name 
2- The second phase involves rasterize shapefile training data 
3- Next, I made segmentation image of the study area 
4- In this phase, I allocated classification to image segmentation 
5- Using random forest algorithm, image was classified to 4 classes 
6- Finally, using test dataset, I obtained the accuracy of the model
