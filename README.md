# Project---Facial-Emotion-Detection

The human face is the most intricate and versatile of all animals. Using our face alone, we can communicate a wealth of information to others.
A smile to show happiness or agreement.
A frown to let someone know you are unhappy.
A lowering of your brows to show someone you are angry or frustrated.
A raise of the eyebrows to ask a question or emphasize a word.
These are all ways that we purposely manipulate the muscles in our faces to show another person a particular message, thought or feeling. With 43 muscles in the face, sitting just under the skin’s surface, they can produce 1000’s of different facial expressions when moved and manipulated.
While many of these expressions will not carry any significant meaning or value to others, there are seven particular facial expressions we should all know about and know how to spot them  the 7 universal facial expression of emotion 
Specifically – **Happy,  Sad,  Anger,  Fear,  Surprise,  Neutral and Disgust**.

# Propsed methodology
1.   Capture Image 
2.   Image Pre-processing 
	-RGB to Gray scale conversion 
	-Scale Normalization 
3.   Crop Feature Regions 
4.   Edge Detection 
	-Prewitt edge detection 
5.   Facial Emotion Classification 

# Algorithm

Step 1: Take a still image of a normal expression pic1 (say) of a human face.
Step 2: Converts the color image to grayscale. 
Step 3: Crop the five facial image region of interest (ROI) (eyes, eye brows and lip) from the image by defining region.
Step 4: Find edges of all image region.
Step 5: Take a still image of a emotional face (angry or happy) pic2 (say) of same person and repeat step 2, 3 and 4.
Step 6: Comparing the deviation of edges of the specified region of pic1 with pic2 by finding the Euclidian distances of coordinate of each pixel.
Step 7: Put the Euclidian distances in a array k (say).
Step 8: Find the standard deviation (SD) from the elements of array.
Step 9: Comparing the SD with pre-define threshold.
Step 10: get the emotions.
