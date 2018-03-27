# Tiny YOLO with pretrained weights in Keras
Implementation of tiny yolo object detector in Keras using pretrained weights


### Dependencies:
1. Python 3.5
2. Keras with Tensorflow backend
3. OpenCV 3

Get yolov2-tiny-voc.weights(Tiny YOLO - VOC 2007+2012) from https://pjreddie.com/media/files/yolov2-tiny-voc.weights or (https://pjreddie.com/darknet/yolov2/)

Place pretrained weights along with tiny-yolo-preTrained.py.

### Run using:
 ```sh
   python tiny-yolo-preTrained.py <imagePath>
 ```
 Example : $ python tiny-yolo-preTrained.py dog.jpg
 
 ### Output:
 Detection probabilities and bounding boxes [xmin,ymin,xmax,ymax] are printed to console.
 
 Image with bounding box and detection drawn is shown in a window.
 
 
 ### Reference:
 https://github.com/experiencor/basic-yolo-keras
