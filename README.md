# Face_Rec_Python

*Use any python version below 3.11. Tested using Python version 3.10.7.*

This is a repository to showcase code for face recognition using python.

1. Download all the files from the latest relase

2. install the following python dependencies : 
     
     1. Open CV Library
        Install command :
        ```pip install opencv-python```

    2. Tensorflow
       Install command :
       ```pip install tensorflow```

   3. Deepface
      Install command :
      ```pip install deepface```
  


   Note - Use Python IDEs to code and execute programs such as PyCharm or VS Code.

_____________________________________________________________________________________________________________________________________________________________________________________________________________

# **EDITING CODE**


1. Add the .xml file to this line :
face_cascade = cv2.CascadeClassifier(PATH TO YOUR haarcascades.XML)

*Note : This file can be found at 
1. Default OpenCV installation folder : 
                C:\Python3x\Lib\site-packages\cv2\data (Windows)
                /usr/local/lib/python3.x/dist-packages/cv2/data (Linux/macOS)

2. Link to the file : 
                                      Open CV GitHub Repo : https://github.com/opencv/opencv/tree/4.x/data/haarcascades
                                      Note : When manually defining the path to the file, use double slahes (C:\\User\\Username-----). This is because in                                                                                                   Python, a single backslash is for escape.*
                                      
3. The change the default code used, change "0" in this line to any number required (mostly 1-3) Note - "0" means the default camera.

   cap = cv2.VideoCapture(0)

5. To change the name of the window that pops up, edit this line :

    window.title("Face Recognition with Details")

6. To change the size of the camera window, change this :

    window.geometry("925x480")

7. Chnage heading font and text of window :

    heading_font = ("Lora", 23, "bold")

    heading_text = "The details of this person are :"

8. Change body font :

   body_font = ("Montserrat", 16) 

9. Edit table contents :

   text_list = [

   ["1", "5", "9"],

   ["2", "6", "10"],

   ["3", " 7", "11"],

   ["4" , "8" , "12"]

   ]


