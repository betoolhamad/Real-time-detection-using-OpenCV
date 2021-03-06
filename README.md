# Real time detection using OpenCV 
Make a real time face detection using Haar Cascades in OpenCV and Python.
So, after install a python and the chose the editor like Anaconda or Pycharm or any other IDE , now you should install the OpenCV library which I installed from PyCharm IDE of python on my compeuter mac OS. <br></br>

**Steps to install OpenCv library:** 

First, from PyCharm IDE go to the File -> new project setting -> preference for new projects , as in the picture :<br></br>

<img width="700" alt="Screen Shot 1442-11-20 at 9 54 50 PM" src="https://user-images.githubusercontent.com/43522153/124016043-e0fbb180-d9ed-11eb-9691-8742e5d7be2f.png">


Second, from python interpreter, chose your project then click the plus icon in the bottom wich means install.  


<img width="700" alt="Screen Shot 1442-11-20 at 2 58 49 PM" src="https://user-images.githubusercontent.com/43522153/124008116-c1ac5680-d9e4-11eb-8f59-a8769f82b635.png">


Third, write **opencv-python** in search bar and click on "install package" button.

<img width="700" alt="Screen Shot 1442-11-20 at 2 58 42 PM" src="https://user-images.githubusercontent.com/43522153/124007443-0d123500-d9e4-11eb-9a53-7877f98279a4.png">


when the installing is successfully, close tabs and start to use it via import the library by written :  <br></br>
`
import cv2
`


<img width="700" alt="Screen Shot 1442-11-20 at 9 12 38 PM" src="https://user-images.githubusercontent.com/43522153/124011693-f3272100-d9e8-11eb-8475-69461852c9c9.png">

**Note :** You can installed the library using terminal and run a following commands:  

To install pip:  
```
sudo easy_install pip
```

To install  package:  

Opencv for python3 run:      

```
pip3 install opencv-contrib-python
```

Opencv for python2.7 run:    
``` 
pip install opencv-contrib-python
````

Then import the package(in python):  

```
import cv2
```

# Face detection using OpenCV

Dependencies to run this program you should save the haarcascade_eye.xml and haarcascade_frontalface_default.xml by click in raw and then click to save as to save it. which we will use to detect the face and eyes.

Here, after I coding and run the program I tested it on my brother to detect his face directly.

And this is the result:


https://user-images.githubusercontent.com/43522153/124594382-66f17f80-de68-11eb-997d-aec3a66e93ac.mov




 


