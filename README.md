# Fruit-detection
Have trained yolo-fastest model in darknet to to detect 8 different types of fruits: (however there are 10 classes)
Apple
Peach
Pomegranate x
Lemon
Mango
Orange
pear        x
Strawberry
Tomato
Watermelon

Approximately 30,000 fruit images to train the model.


# 2Tensorflow
contains code for converting darknet model to tensorflow keras.
The code is from https://github.com/david8862/keras-YOLOv3-model-set.
command: python convert.py yolo-fastest.cfg yolo-fastest.weights weights/yolo-s.h5


# 2Tflite
contains jupyter notebook for converting tensorflow keras to tflite model.


# Thanks
https://github.com/dog-qiuqiu/Yolo-Fastest

https://github.com/AlexeyAB/darknet
