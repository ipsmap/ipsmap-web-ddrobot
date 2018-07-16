# 道一循大屏机器人H5接入文档

---

本url为道易寻大屏机器人服务网址，提供院方在医院内的大屏机器的H5网页扫码导航。

* #### 应用场景S1 - 开启某场域地图并提供poi搜索与扫码手机导航服务

##### URL：

[https://dp.ipsmap.com?robotId=bbPwfYSosX](https://dp.ipsmap.com?robotId=bbPwfYSosX)

##### URL Params：

robotId:机器人的id，根据这个id可打开不同场域的地图，并显示该场域下robotId对应的机器人的位置信息，以广妇儿为例



* #### 应用场景S2 - 与机器人交互，获取机器人的语音识别的具体位置的id，根据该id查找对应的科室，并进行显示与导航。

##### URL：

[https://dp.ipsmap.com?robotId=bbPwfYSosX&targetId=skvoexiL3V](https://dp.ipsmap.com?robotId=bbPwfYSosX&targetId=skvoexiL3V)

##### URL Params：

robotId:机器人的id，根据这个id可打开不同场域的地图，并显示该场域下robotId对应的机器人的位置信息

targetId:根据词汇表对应的id，传入该id会获取该id对应的词语，根据该词语搜索具体的科室结果，在列表中显示（多个结果按距离显示），默认选中第一个。  这里以 广妇儿的 哺乳间 为例。



#### 

 

