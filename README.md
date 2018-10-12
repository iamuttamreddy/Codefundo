Heat waves are extended periods of extremely hot weather that have a major impact on human health, socio- economics and natural systems. Heat waves were the most prominent hazard in Europe causing more than 70,000 excess deaths during the extreme summer of 2003. Heat waves and hot weather are potentially fatal and can aggravate existing health conditions. We aim to identify the population that might be at risk during a heat wave and caution them regarding the possible deleterious effect it might have on their health.
We propose an intelligent model to evaluate the risk associated with a heat wave. In order to answer how severe a heat wave is, it is important to consider intra-urban variability of the hazard, as well as the local socio- economic factors and their geographical variation. LST images give the spatial temperature distributions and are a very vital part of climatology analysis. LST instances are fit into an urban climate model which considers other supporting data for risk prediction. Subsequently, heat wave events are identified, and relevant parameters are calculated, including their intensity, duration and time lag between two consecutive events. Artificial intelligence fuzzy logic was then used to characterise each heat wave event from mild to extreme (Classification of heat wave events). The accumulated monthly result was the monthly spatial distribution of heat wave hazard and the risk associated for a specific population are analysed.


DATASETS
The fuzzy model proposed for heat wave hazard classification and risk assessment requires the following datasets for tuning the model:-
1.	MODIS Terra and Aqua summer images
The thermal bands from these images serve as an essential parameter in generating Land Surface Temperature maps. These maps have been achieved as a part of Urban Heat Islands and Thermography Project during heatwave conditions.

2.	ECMWF ERA-Interim Dataset
This data set is used to analyze the temperature and wind field variations during heat waves.

3.	Land Surface Analysis Satellite Applications Dataset
The data is used to analyze long and short term surface radiation fluxes during heat waves. The fraction of water content in each model grid is derived from the dataset.

4.	VITO vegetation archive
The Normalized Difference Vegetation Index accounted for the changing vegetation during the summer heat wave season is enlisted in the dataset.

5.	Census data
Country specific data can be separately fed during prediction time to analyze the risk for the particular region.





TECHNOLOGY STACK

1.	GDAL python package
Package used to process the thermal MODIS images and separate out the required bands from the image.
2.	Tensorflow and Keras
Python libraries used for developing fuzzy models
3.	Opencv 3.6.5
Python library for image processing used to generate LST maps from the separated image.
4.	Numpy package
Support package used along with Opencv
5.	Microsoft Azure
Cloud used for training the model and deployment of the application.
