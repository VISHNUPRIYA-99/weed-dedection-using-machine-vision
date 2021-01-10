# weed-dedection-using-machine-vision


The main aim of this project is to identify the location of weeds among crops. The approach of the project includes  achieving a baseline method for developing a real time weed detection system through binary classification. Image is captured using  camera, The digital images were captured in outdoor light conditions with perspective projection over crop. Captures have 8MP resolution in RGB color space with JPG extension.  The captured image is converted to HSV image. Then image is segmented using excessive green colour segmentation. Further image is converted  into gray scale image. Grey scale image is given as input to ‘Gray level co-occurrence matrix’.
•	  Contrast
•	  Correlation
•	  Energy 
•	  Homogeneity

HSV image of weed:

Hue is therefore the actual color. Brightness refers to how much white or black  is mixed in the color, while Saturation  indicates  the amount of grey in a color. A saturation value of 0 indicates mostly grey while 100% luminosity (or L = 255) is white.
H - Hue	
S - Saturation
V – Value

Segmented image of weed:

In computer vision, image segmentation is the process of partitioning a digital  image into multiple segments . The goal of segmentation is to simplify and  change the  representation of an image into  more meaningful and easier  image to analyze.

Gray image of the weed:

A gray scale  image is simply one in which the only colors are shades of gray. The reason for differentiating  such  images from any other sort of color image is that less information  needs to be provided for each pixel. 

The proposed system ensures the presence of weed by contrast, color, homogeneity. The image captured is processed using machine vision and plant is identified either to be crop or weed by image segmentation. The final gray image indicates the presence of weed, the location of weed is clearly identified and pesticide is sprayed to diminish the growth of weed. The system enhances growth of crops and increases the yield. The system uses rotating camera and avoids obstacles during weed detection. 
