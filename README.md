# Traffic-Sign-Detection-and-Classification
Traffic-Sign-Detection-and-Classification

To Detect Traffic Sign, YOLOv5 is used to retrain with the German Traffic Sign Detection Benchmark dataset & yolov5s6.pt pre-trained model. To classify the sign, Simple CNN model is used with help of TensorFlow Keras.

Dataset Link: https://benchmark.ini.rub.de/gtsdb_news.html

# Run Detection

To run the detection, I modified the detect.py file.
>> python detect.py --weights best_traffic_sign.pt --img 1280 --source input_file
