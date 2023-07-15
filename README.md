
# Number Plate Detection 

This code is used for detection of Number plate of vehicles. 
A haar cascade classifier is an effective object detection method. It is a machine learning based approach.

## How does it works?

To detect license number plate in an image, we could follow the below steps-

* Import the required library. In all the following examples, the required Python library is OpenCV. Make sure you have already installed it.

* Read the input image using cv2.imread(). Specify the full image path. Convert the image to grayscale image.

* Initiate the Haarcascade classifier object plate_cascade = cv2.CascadeClassifier() for number plate detection. Pass the full path of the haar cascade xml files. You can use the haar cascade file haarcascade_russian_plate_number.xml to detect the number plate in the image.

* Detect the number plate in the input image using plate_cascade.detectMultiScale(). It returns the coordinates of the detected number plate in (x,y,w,h) format.

* Draw the bounding rectangles around the detected number plate in the original image using cv2.rectangle().

Display the image with the drawn bounding rectangles around the license number plate.

## Screenshots

![image3](https://github.com/singhyash3302/number-plate-detection-/assets/26682113/be8637b5-582f-48e9-a834-ca39f107543c)
![image2](https://github.com/singhyash3302/number-plate-detection-/assets/26682113/99f4983c-e888-44fa-b7ed-e98fd3641b80)
![image_1](https://github.com/singhyash3302/number-plate-detection-/assets/26682113/2c96f852-4340-4299-8967-ca8804d97a48)


