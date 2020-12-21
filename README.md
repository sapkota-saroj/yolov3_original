************************** README ******************************
1. clone the yolov3_original: 
2. $ cd yolov3_original
3. $ git checkout Yolo_v3
4. $ make
5. Download weight file from the link wget https://pjreddie.com/media/files/yolov3.weights
6. object detection from video: $ ./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights <video.mp4> => Display bounding box along with class
7. Real time object detection: $ ./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights => Display bounding box along with class
