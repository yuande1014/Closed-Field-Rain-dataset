Pixel-wise Content Attention Learning for Single-Image Deraining of Autonomous Vehicles
====
Abstract—Improving the performance of autonomous vehicles in adverse weather conditions is vital for the commercialization of such automated systems. Existing synthetic datasets for developing rain-tolerant vision are of limited value. To address this deficiency, a closed environment capable of simulating different degrees of rainfall is constructed. And a new Closed Field Rain dataset is collected in 36 testing cycles. Inspired by the idea that human can infer the content of rainy images directly without removing the raindrops. A new single-image deraining method is proposed, that does not require ground truth images. This method incorporates an image content estimation module applied to predict the scene content representation, a pixel-wise content attention block used to evaluate the significance of each pixel. After that, an encoder-decoder network is applied to complete the image. On the other hand, it is almost impossible to obtain the ground truth of rainy images because of the dynamic characteristics of real traffic environment. Thus, the model is trained by employing PatchGAN, using a patch-based loss. Using common no-reference and feature point metrics as performance indicators, This paper conducts a comprehensive evaluation on both synthetic and Closed Field Rain datasets. Results show the effectiveness of our model quantitatively and qualitatively.

Two kinds of data are included in the dataset: Stationary, and Moving
In Stationary Data, the videos are captured in conditions of moderate rain, heavy rain, and torrential rain, with the distance between the camera and target set to be 5 m, 10 m, 15 m, 20 m, 25 m, and 30 m in different testing cycles. Thus, driving data from 36 testing cycles are obtained.
In Moving Data, the videos are captured in conditions of moderate rain, heavy rain, and torrential rain, with the vehicle speed set to be 10 km/h, 15 km/h, 20 km/h, 25 km/h, 30 km/h, and 35 km/h in different testing cycles. Thus, driving data from 36 testing cycles are obtained.

Naming rule: moving_dummy: Moving Data captured in conditions that the traffic target is a dummy
             moving_vehicle: Moving Data captured in conditions that the traffic target is a vehicle
             static_dummy: Stationary Data captured in conditions that the traffic target is a dummy
             static_vehicle: Stationary Data captured in conditions that the traffic target is a vehicle
             
Download Link: https://pan.baidu.com/s/1C0BcodvzA4AbI4NDD0Og_w 
Access Code：3pm9


