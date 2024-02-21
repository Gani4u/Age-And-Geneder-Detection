# Gender-and-Age-Detection

# About the Project :
In this Python Project, We had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. We used the models trained by Tal Hassner and Gil Levi. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions

# Dataset :
For this python project, I had used the Adience dataset; the dataset is available in the public domain and you can find it [here](https://www.kaggle.com/datasets/ttungl/adience-benchmark-gender-and-age-classification)

# Additional Python Libraries Required :
1 OpenCV - pip install opencv-python
2 argparse - pip install argparse

# Usage :
1 Download my Repository <br />
2 Open your Command Prompt or Terminal and change directory to the folder where all the files are present.<br />
3 Detecting Gender and Age of face in Image Use Command : python detect.py --image <image_name><br />
Note: The Image should be present in same folder where all the files are present<br />
4 Detecting Gender and Age of face through webcam Use Command : python detect.py<br />
Press Ctrl + C to stop the program execution.
