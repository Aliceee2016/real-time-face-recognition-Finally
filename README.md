# real-time-face-recognition
#我使用的模型链接:https://pan.baidu.com/s/1K5oao8bS2_qoV86_XaHpeA  密码:akoj


每个人三十多张图比较好
加入了自己训练模型的代码，之前看不懂就没有加
train_softmax.py中如下参数设置比较合适
batch_size = 90
max_nrof_epochs = 500
image_size = 160
epoch_size = 1000

人脸检测基于：mtcnn：Joint Face Detection and Alignment using Multi-task Cascaded Convolutional Neural Networks
人脸识别基于facenet
