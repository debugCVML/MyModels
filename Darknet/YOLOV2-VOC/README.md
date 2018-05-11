# 模型说明

该模型是使用YOLOv2进行训练的，数据是使用的VOC数据库，整个过程根据[YOLOv2官网](https://pjreddie.com/darknet/yolov2/)介绍。

整个模型存在的问题是，类别名称搞错了，但是准确度还行。

使用单块1080TI显卡，在有两个E5至强CPU服务器上训练了18个小时，实际上应该是fine turn。

网络参数是使用的./cfg/yolo-voc.2.0.cfg。不知道整个玩意与yolov2有啥不一样。