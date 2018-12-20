
## 前言
网上大多的ncnn的vs版本代码都比较老，同时为了在Windows下单步调试学习mtcnn模型，因此把网上的资源整合了一下，分享出来。

## 使用


直接git clone 到本地，然后使用vs2017打开ncnn文件夹下的ncnn.sln。（依赖的Opencv库在opencv343下）
* 1、解压opencv343\x64\vc15\bin\opencv_world343d.rar 到 ncnn\x64\Debug
* 2、生成可执行文件
* 3、查看结果

注：目前只测试了test_picture函数，test_video并未测试

## 程序执行效果


![待检测图片](https://github.com/zjd1988/mtcnn_vs2017_based_on_ncnn/blob/master/sample.jpg)
![检测结果](https://github.com/zjd1988/mtcnn_vs2017_based_on_ncnn/blob/master/face_detection_result.jpg)




## 鸣谢

* 1、 https://github.com/Tencent/ncnn
* 2、 https://github.com/moli232777144/mtcnn_ncnn
* 3、 https://github.com/ElegantGod/ncnn
