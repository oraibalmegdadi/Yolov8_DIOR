# Applying Yolov8 Object Detection Model to DIOR Dataset
DIOR is a large-scale benchmark dataset for optical remote sensing image target detection proposed on the research paper "**Object detection in optical remote sensing images: A survey and a new benchmark**" [1] . The dataset contains around 20Kimages, with an image size of 800×800 pixels and covers 20 object classes.
These 20 object classes are: Wind mill, Vehicle, Train station, Tennis court, Storage Tank, Ship, Harbor, Stadium, Ground Track Field, Golf course, Expressway toll station, Expressway service area, Dam, Chimney, Bridge, Overpass, Basketball Court, Baseball field, Airport, Airplane.







# Yolo (You only look once)

YOLO is an object detection and image segmentation model, was developed by Joseph Redmon and Ali Farhadi at the University of Washington. Launched in 2015, YOLO quickly gained popularity for its high speed and accuracy. is available in various versions, each offering unique features and improvements. 
![image](https://github.com/oraibalmegdadi/Yolov8_DIOR/assets/4184460/dbbb69b0-76f4-4217-bbcc-1c4855be1ac3)
*Yolo different version/ Performance [2]*

We choose Ultralytics YOLOv8 as a state-of-the-art model that builds upon the success of previous YOLO versions and introduces new features and improvements to further boost performance and flexibility. YOLOv8 is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and tracking, instance segmentation, image classification and pose estimation tasks.



#Traning 
The dataset splitted to 70% tranning, 15 Validation, 15% test
The model run for 10 epochs 

#Traning Reuslts
![results](https://github.com/oraibalmegdadi/Yolov8_DIOR/assets/4184460/2d24d0f9-c626-4438-b04a-452b79e8fbb4)

![image](https://github.com/oraibalmegdadi/Yolov8_DIOR/assets/4184460/325ccd94-5948-457c-9853-b4245c3256c2)




[1] https://www.sciencedirect.com/science/article/abs/pii/S0924271619302825

[2] https://github.com/ultralytics/ultralytics
