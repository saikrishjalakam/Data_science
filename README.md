# object_detection_yolov5_custom_data-
I have scraped all the uniformed_personnel images(ex: military, navy, air forces, police men, lawyer, student etc..,) nearly making 12 classes.
Annotated all the images using labelimage and segregated the data into train, test. Accordingly prepared the XML files and converted them into txt.files.
Later cloned the YOLOV5 repository for ultralytics github page(https://github.com/ultralytics/yolov5). As my dataset is of medium size.. I proceeded with YOLOVS5 - which is a small version.
Using the transfer learning had built model on 500 epochs, with batch size of 8 and classes 12.
Since, YOLOV5 is the latest version in the field of object detection, Time taken and accuraction of detection is ultimate.
YAML file is the route map for this yolo model, So need to cautious in creating a yaml.file . 
