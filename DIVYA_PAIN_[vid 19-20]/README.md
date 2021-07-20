PROJECT TITLE

AI-ML-for-Newborn-Babies-in-Healthcare

ISSUE

PAIN [vid 19-20] #21

GOAL

The goal of the project to develop a Machine Learning algorithm for classifying the facial expressions of Newborn babies in the Hospital as per the Pain Scale Assessment on a scale of 10.

PURPOSE

The purpose of this issue was to extract 50 images each from both videos and convert them to grayscale images. Later, classify those images into 3 categories namely No-Mild, Moderate and Severe based on the facial expressions of the babies.

DATASET

Videos 19-20 from Pain folder in DATASET (https://livemissouristate-my.sharepoint.com/:f:/g/personal/nyc10040_missouristate_edu/Ev2GCLuXRK1DsgbeiRGRywkBBzLLqRH-OKaMi3rFHuM3iA?e=Zm3XcU)

PROCEDURE

I have downloaded the required dataset from the link in ZIP format. Later, stored those videos in the ai_ml_babies folder on my local machine.

Written the code to extract 50 images collectively.

LIBRARIES REQUIRED

*cv2

*os

*glob

Compilation steps:

-> I made an empty list which can store all the videos of the dataset, for my case it was 19 and 20

-> Extract images from each video.

-> Save the images in specific folder.

->For colored, I stored it in a folder named colored_folder.

-> Convert the images into grayscale.

->For grayscale pictures, I stored it in the gray_folder

Classified total 100 images into 3 different folders based on the expressions.

UNDERSTANDINGS FROM THE WORK

Got a clear understanding on how to use os module to get to different folders, basically how to interact with the OS.

Got to learn how glob is used.

Working with opencv was completely new and something that I haven't tried before so it was quite fun extracting the images of the children.

Learnt how to capture different frames from a video using cv2.VideoCapture().

Learnt how to save the extracted images using cv2.imwrite().

To convert colored image to Grayscale, I have used cv2.cvtColor( _ , cv2.COLOR_BGR2GRAY).

RESEARCH

I did some reasearch as to why babies suffer from these kind of pain and how opencv can help in such cause. The child's eyes gave me the clear picture to classify them into moderate, mild, or severe pain.


CONCLUSION

I have extracted 100 images from 2 videos and classified them into 3 folders as per the expressions.

This dataset can be used to train the model which can predict the risk of survival of the Preterm newborn babies through Pain-Scale Assessment technique.

The output of my work is in Image_Datasets folder.


REFERENCES

https://theailearner.com/2018/10/15/extracting-and-saving-video-frames-using-opencv-python/


https://theailearner.com/2018/10/06/read-write-and-display-images-with-opencv/


https://theailearner.com/2018/10/07/read-write-and-display-videos-with-opencv-python/


NAME OF AUTHOR

Divya Choudhary
