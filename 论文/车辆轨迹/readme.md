
GPS轨迹|车辆路径拼接&还原&预测相关论文


* SIGSPATIAL 2021 《Vehicle trajectory recovery on road network based on traffic camera video data》 https://dl.acm.org/doi/10.1145/3474717.3483987
【点评】充分利用城市各个角落的普通监控相机进行车辆轨迹的时空拼接还原。首先利用车辆图像识别聚类从不同相机的图像中找到同一辆车，形成初试的车辆路径，其次根据初试路径结合路网拓扑时空信息利用隐马尔可夫算法还原车辆在路网中的完整轨迹。循环迭代以上两步直至收敛，完成最终的车辆轨迹结果，最后转化成路段-路段 or 交叉口-交叉口的轨迹格式输出。

* 同济大学2022 《Realtime wide-area vehicle trajectory tracking using millimeter-wave radar sensors and the open TJRD TS dataset》https://www.sciencedirect.com/science/article/pii/S2046043022000247 【点评】国内单车轨迹的公开数据集介绍；其他数据集还有

![截屏2022-10-22 15 21 47](https://user-images.githubusercontent.com/28177991/197326239-95579697-d81c-4c4f-bf80-7f8f40b9be68.png)




|   publication|location   | trajectory length  | avilability  | link  |
|--------------------------|--------------------|-—------------|----------------------------------------------------------|
| NGSIM        |  highways US |  640 meters     |  yes         | https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm  |
| Krajewski2018|  highways german |  420 meters |  yes         | https://www.highd-dataset.com/#  |
| barmpounakis |  urban roads greece |  350 meters     |  yes         |https://open-traffic.epfl.ch/  |
| HIGH-SIM |  Highways US  |  2438 meters     |  yes         |https://github.com/CATS-Lab-USF |


* 2021 《A Car Following-Based Method for Vehicle Trajectory Connection》https://www.researchgate.net/publication/353286341
