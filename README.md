# CNN-for-Classifying-Skin-Cancer-as-Benign-or-Malignant
A simple CNN that achieves and accuracy of 81.212% for classifying skin cancer as benign or malignant. Made with Keras and TensorFlow. 

ACKNOWLEDGEMENTS

The original source of the data can be found here: https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign
Much of the tools and techniques I used for this project can be found here: https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-to-classify-photos-of-dogs-and-cats/

Jason Brownlee really has an amazing website for tutorials, so be sure to check out Machine Learning Mastery (he also writes books).

MOTIVATION & GOALS

As I become more interested in machine learning, I wanted to try out a classification problem, but one that had real-life applications and impact. A machine learning application for identifying skin cancer as benign or malignant could save many lives and counter human error. After an eventful January full of hackathons and side project, I took a break in February. This small project is an attempt to ease myself back into programming after many meaningful naps and Netflix binges. 

TOOLS USED

* Made in a Jupyter notebook
* matplotlib for peeking at the photos and visualizing cross entropy loss and accuracy (in graphs also uploaded as a .png to the repository)
* Keras, especially it's preprocessing library which made everything a whole lot easier and quicker
* Tensorflow

TECHNIQUES USED

Used dropout and horizontally flipped the images in the dataset to improve accuracy.

ISSUES FACED

I still can't figure out how to save my model with model.save(filepath) from Keras. Any help on that would be amazing. Also, I really had to fiddle with the dropout weights to get a desirable number for accuracy. Some more background on dropout may give me greater intuition for hyperperameter tuning in the future.


FUTURE?

In the future, I would love to integrate this model into a mobile application that healthcare professionals or patients alike can use everyday. I think my next project just might be a mobile application that leverages machine learning. 🤔 Stay tuned.
