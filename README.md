# landcovermapping-Fiji
A developing country, Fiji is facing rapid urbanisation. However, it has been identified that technical support for urban planning is inadequate for most municipal councils. This study detected and compared land use and land cover change in Nadi, Fiji, from 2013 to 2019. The ultimate goal of this study is to provide technical support in land cover/land use modelling and change detection. We used the free open-access Landsat-8 OLI 30m resolution images and created our own data labels for supervised learning. We evaluated supervised learning algorithms based on the 2013's satellite image. The classification accuracies for all three models were high. ANN had an accuracy of 94.857%, RF had an accuracy of 96.952%, and CNN had an accuracy of 99.05%. Using the Google Earth Engine build-in function, an unsupervised learning algorithm K-means was also tried for generating the land cover map. The assessment scores and the resulting land cover maps were carefully compared, and we chose the Convolutional Neural Network for classifying the land cover types of the rest years' images. We finally present a visualisation of change detection, highlighting urban area changes over time to monitor changes in the map.

![Input](https://github.com/DARE-ML/landcovermapping-Fiji/assets/122882976/780c6aea-c76a-4605-883f-54cf7eafbbcf)

2013 land cover map
<img width="213" alt="image" src="https://github.com/DARE-ML/landcovermapping-Fiji/assets/122882976/ffbd0dfa-0efb-4a36-9345-13ff71d7aace">

2013-2019 land cover map
![image](https://github.com/DARE-ML/landcovermapping-Fiji/assets/122882976/fed044d3-9836-47a9-8acd-9eca523145aa)

2019 land cover map
<img width="213" alt="image" src="https://github.com/DARE-ML/landcovermapping-Fiji/assets/122882976/41871f21-9e96-4083-84bc-7fc07c34894f">

