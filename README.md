# SPC-DTW

Figure shows the general idea of the SPC-DTW method. Firstly, 12 months of maximum NDVI time series data were calculated using 2022 Sentinel-2 images to minimise the effect of cloudiness. Secondly, class probability constraints for sugarcane were calculated using the corresponding training sample points and the random forest method to provide time penalty weights for the subsequent acquisition of sugarcane information. Finally, the sugarcane time series curves were constructed by combining the intra-annual growth cycle of sugarcane, and the weighted DTW was calculated for the sugarcane phenology in January-February and November-December, and then suitable threshold was selected to obtain the 2022 10 m sugarcane mapping results.

 liuchengtu.png
Figure. The process of the SPC-DTW method


