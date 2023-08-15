#  Industrial Smoke Detection using YOLO Algorithm (Computer Vision)
You Only Look Once (YOLO) is a real-time object detection algorithm. It is a single-shot 
detector, which means that it can detect objects in a single pass through the image. This 
makes YOLO very fast, and it can detect objects at speeds of up to 45 frames per second.

## How YOLO can be used in smoke detection in industries:
* A camera is placed in a strategic location in the industry.
* The camera is used to capture images of the environment.
* YOLO V5 or V8 is used to detect smoke in the images.
* If smoke is detected, an alarm is triggered.
* This process can help to prevent fires and other accidents in industries

## Procedure for Creating a Custom Data Set:

1. Gather your images and annotations
2. Split your data into a training set, a validation set, and a testing set
3. Preprocess your data
4. Augment your data
5. Generate a version

## All these steps were being carried out on 2 tools:

1. [Roboflow](https://roboflow.com/)
2. [CVAT](https://github.com/openvinotoolkit/cvat)

## Testing Images Output with YOLO 8
![download](https://github.com/esarvesh11/Industrial-Smoke-Detection-using-YOLO-Algorithm-Computer-Vision/assets/102407237/1364c042-4a5c-471e-84fa-20273b6ff7b2)

## Smoke Colour Detection Intensity Using YOLO V8 Algorithm

![Screenshot 2023-08-15 162040](https://github.com/esarvesh11/Industrial-Smoke-Detection-using-YOLO-Algorithm-Computer-Vision/assets/102407237/1b251db5-2d0b-49d0-aa93-c32745702407)

* Intensity (White Smoke Image): 0.2228
* Intensity (Black Smoke Image): 0.6337

## Identifying Coordinate with Maximum Intensity

![Screenshot 2023-08-15 162622](https://github.com/esarvesh11/Industrial-Smoke-Detection-using-YOLO-Algorithm-Computer-Vision/assets/102407237/25a64f1a-8f62-4576-9700-2abe210fd9e5)

* Coordinates of the pixel with maximum intensity: Row:189 

## Conclusion
* The implementation of the YOLO algorithm for industrial smoke detection proved to 
be a valuable solution for preventing potential hazards in industries. 
* Through the V8 model, the project achieved significant progress in 
accurately detecting smoke instances.
* The use of the [Roboflow](https://roboflow.com/) application facilitated dataset annotation, while data augmentation techniques improved the model's generalization capabilities. 
* Additionally, the ability to differentiate between black smoke and white smoke further enhanced the model's capabilities. 
* The integration of intensity analysis within the bounding box provided valuable insights into the smoke detection process. 
* Overall, this project showcased the potential of YOLO algorithms for industrial smoke detection, contributing to improved safety measures in industrial environments.
