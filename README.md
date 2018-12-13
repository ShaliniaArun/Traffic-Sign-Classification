# Traffic-Sign-Classification

# Abstract

Traffic signs are an integral part of our road infrastructure. They provide critical information, sometimes compelling recommendations, for road users, which in turn requires them to adjust their driving behaviour to make sure they adhere with whatever road regulation currently enforced.

Without such useful signs, we would most likely be faced with more accidents, as drivers would not be given critical feedback on how fast they could safely go, or informed about road works, sharp turn, or school crossings ahead. In our modern age, around 1.3M people die on roads each year. This number would be much higher without our road signs. 

Naturally, autonomous vehicles must also abide by road legislation and therefore recognize and understand traffic signs.

Traditionally, standard computer vision methods were employed to detect and classify traffic signs, but these required considerable and time-consuming manual work to handcraft important features in images. Instead, by applying deep learning to this problem, we can create a model that reliably classifies traffic signs, learning to identify the most appropriate features for this problem by itself. 

# Dataset Description

The dataset features 43 different signs under various sizes, lighting conditions, occlusions and is very similar to real-life data. Training set includes about 39000 images while test set has around 12000 images. Images are not guaranteed to be of fixed dimensions and the sign is not necessarily centered in each image. Each image contains about 10% border around the actual traffic sign.

Then download ‘Images and annotations’ for training and test set from GTSRB website and extract them into a folder. Also download ‘Extended annotations including class ids’ file for test set. 
