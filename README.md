# Mask-Rcnn-Tensorflow-2.0

Now a days tensorflow 2.0 is taking over the world and object detection algorithms are the things in which researchers, students and indutries are intrested alot. So
I decides to make a mask-rcnn compatible with tensorflow 2.0. I took help from alot blogs tensorflow 2.0 documentations and stack-overflow. Now a days its really 
complicated to made a tensorflow code which is compatible with nvidia 3000 series. So I also made some changes to make this code run on my 3070rtx. So tighten your 
seat belts, we are going to start our drive.



# Making Dataset.
First step is to mannotate data I used VIA image annotator (https://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.1.html) to annotate my data I make a rectangle against every object and save the project in json


## Augmentation:

After doing all the annotation things I rotate the image and box at every angle (0, 360) you can easily use my notebook to get done with your annotations.

## Training

After training Just opent he training notebook give the path of the parent folder where your augmented train and val located and start the training.

## Evaluation

Now open the prediction notebook and just run the cells after specefiying weights paths and images path.


## Feel free to ask any question Thank you
