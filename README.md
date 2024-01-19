# Driver-Drowsiness-Detection-System-

ABSTRACT: 

Drowsiness detection is an important research area in the field of computer vision and driver safety. It involves the use of image and video 
processing techniques to detect signs of drowsiness in drivers, such as drooping eyelids or changes in facial expression. This can help to 
prevent accidents caused by driver fatigue, which is a leading cause of road accidents worldwide. Recent advances in deep learning and 
neural networks have led to significant improvements in the accuracy and reliability of drowsiness detection systems, making them an 
increasingly important tool for improving road safety. These systems are now widely used in the automotive industry, and are also being 
explored for use in other applications, such as aviation and industrial safety. 

PROPOSED SYSTEM:

This system uses CNN (Convolutional Neural Network), Python, and Open CV to determine whether the driver is sleepy. Here, we developed a 
system that can recognize features on a driver's face and notify them if they nod off while operating a vehicle using Python, OpenCV, and 
Keras (tensor flow). When it detects whether the eyes are open or closed, the system prompts. The alarm will sound to alert the driver—
who is likely sleepy—to stop if their eyes are closed for three seconds. A CNN network that we built has been trained on a dataset that 
distinguishes between closed and open eyes.  Then Open CV is used to get the live fed from the camera and run that frame through the CNN 
model to process it and classify weather it opened or closed eyes.
1. Haar Cascade classifier is used for object detection. It is used to extract eyes from the driver’s face and given as input to CNN.
2. Deep features are extracted using CNN with four convolutional layers, and those features are then sent to fully connected layer.
3. CNN classifies the photographs as having closed or open eyes using the Soft Max layer.

DATA COLLECTION :
The dataset which was used is a subnet of a dataset from(https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset)

The following  HaarCascades XML files are used to  identify objects or features within images or video frames.
  1.haarcascade_frontalface_default.xml
  2.haarcascade_ lefteye_2splits.xml
  3.haarcascade_righteye_2splits.xml

LIBRARIES USED:
  OpenCV
  Keras
  Pandas
  Numpy
  OS

OUTPUT:


![Screenshot (526)](https://github.com/AkshayaRobbi/Driver-Drowsiness-Detection-System-/assets/149946045/f9d1295c-75f4-49ff-9a34-1a7a0e468e8a)

![Screenshot (503)](https://github.com/AkshayaRobbi/Driver-Drowsiness-Detection-System-/assets/149946045/d0051901-602e-41d0-8926-eee20c5869d0)

![Screenshot (505)](https://github.com/AkshayaRobbi/Driver-Drowsiness-Detection-System-/assets/149946045/2ca56068-458e-4cff-8564-99af051fabf9)

![Screenshot (517)](https://github.com/AkshayaRobbi/Driver-Drowsiness-Detection-System-/assets/149946045/ca62aa55-0b6e-4362-a5cd-4868f764ee11)



