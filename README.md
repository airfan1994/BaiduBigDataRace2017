2017年百度大数据竞赛源码 获得优秀奖(10/1459)
2017年的百度大数据竞赛是一个细粒度图像识别的题目，识别出100种狗的细分种类：
主要思路包括：
1、使用数据增强扩充图片
2、使用fast-rcnn切割图片，将数据分为全图，狗身，狗头三部分。将三部分特征级联
3、采用投票策略集成resNet,Inception,Xception和denseNet等模型
详见文档