Muhammad Haseeb Ishaq
2021389

AI-211 : Introduction to Artificial Intelligence

Project Title: Face Emotions Recognition
Readme File for Project.

Project has the following stages:
1. Collecting Images with Expressions
2. Detecting Faces in the Images and saving them
3. Training our classifier on the Faces
4. Recognition of expression in new Images

In my project, I have used various machine learning algorithms to execute the final result.
Firstly, I have cloned the git repository, "https://github.com/misbah4064/facial_expressions.git" to extract all relative directories and the dataset file.

The Dataset used here is the famous dataset used for facial emotions recognition, Face Emotions Recognition, 2013.

You are suppose to create another directory which contains five folders of all five emotions i.e. sad,happy,anger,neutral and surprise which my model will be detecting by the end. 
In data preprocessing stages, we are supposed to push all of the images of dataset under their respective related category i.e. to which they belong. For Example, all images of happy faces will be pushed into the folder of happy which we created in directory. This process should be repeated for all mentioned emotions.

Afterwards, in another directory i.e. "Dataset" we would be collecting all of the cropped faces present in the images and then decoloring the image on a grey scale. Afterwards, all faces are scaled on several parameters and passed through 'haar cascade classifier' i.e. the clasifier that recognizes various facial features by identifying patterns of pixels. This classifier identifies the image and then image is saved in the created directory with similar  defined labels.

In the next stage, all of the images are trained by cv2.CascadeClassifier("haarcascade_frontalface_default.xml") and Local Binary Pattern Histogram (LBPH). These two are the very significant techniques, which uses machine learning algorithms and are used to identify emotions by image processing. 

After the data is trained, an image is given to the model as input. The model then identifies the faces in that image, draw the rectangle around the faces and predicts the emotion of each face by a certain percentage and accuracy. The model also portrays its working graphical user interface (GUI).

This sums up the whole working of my model.

