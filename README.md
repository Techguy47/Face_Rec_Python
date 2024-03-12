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

# **Editing Code**


1. Add the .xml file to this line :
face_cascade = cv2.CascadeClassifier(PATH TO YOUR haarcascades.XML)

*Note : This file can be found at 
2. Default OpenCV installation folder : 
                C:\Python3x\Lib\site-packages\cv2\data (Windows)
                /usr/local/lib/python3.x/dist-packages/cv2/data (Linux/macOS)

3. Link to the file : 
                                      Open CV GitHub Repo : https://github.com/opencv/opencv/tree/4.x/data/haarcascades


   Note : When manually defining the path to the file, use double slahes (C:\\\User\\\Username-----). This is because in                                                                                                   Python, a single backslash is for escape.*
                                      

4. To change the default camera used, edit line : 10
  
   Note - "0" means the default camera.

   ```cap = cv2.VideoCapture(0)```

5. To change the name of the window that pops up, edit line : 14

    ```window.title("Face Recognition with Details")```

6. To change the size of the camera window, edit line : 15

    ```window.geometry("925x480")```

7. To chnage heading font and text of window, edit line : 17 & 18

    ```heading_font = ("Lora", 23, "bold")```

    ```heading_text = "The details of this person are :"```

8. To change body font, edit line : 23

   ```body_font = ("Montserrat", 16)``` 

9. Edit table contents :

   text_list = [

   ["1", "5", "9"],

   ["2", "6", "10"],

   ["3", " 7", "11"],

   ["4" , "8" , "12"]

   ]


