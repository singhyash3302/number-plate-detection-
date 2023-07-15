
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

