# Face_Rec_Python

*Use any python version below 3.11. Tested using Python version 3.10.7.*

This is a repository to showcase code for face recognition using python.

1. Download all the files from the latest relase

2. install the following python dependencies : 
     
     1. Open CV Library
       
        Install command :

        ```pip install opencv-python```

    3. Tensorflow

       Install command :

       ```pip install tensorflow```

   4. Deepface

      Install command :

      ```pip install deepface```
  


   Note - Use Python IDEs to code and execute programs such as PyCharm or VS Code.

_____________________________________________________________________________________________________________________________________________________________________________________________________________

# **Using the Code**


1. Add the .xml file to this line :
face_cascade = cv2.CascadeClassifier(PATH TO YOUR haarcascades.XML)

*Note : This file can be found at : https://github.com/opencv/opencv/tree/4.x/data/haarcascades *

Default OpenCV installation folder : 

C:\Python3x\Lib\site-packages\cv2\data (Windows)

/usr/local/lib/python3.x/dist-packages/cv2/data (Linux/macOS)


2. To change the default camera used, edit line : 10
  
   Note - "0" means the default camera.

   ```cap = cv2.VideoCapture(0)```

3. To change the name of the window that pops up, edit line : 14

    ```window.title("Face Recognition with Details")```

4. To change the size of the camera window, edit line : 15

    ```window.geometry("925x480")```

5. To chnage heading font and text of window, edit line : 17 & 18

    ```heading_font = ("Lora", 23, "bold")```

    ```heading_text = "The details of this person are :"```

6. To change body font, edit line : 23

   ```body_font = ("Montserrat", 16)``` 

7. Edit table contents :

  ```text_list = [```

   ```["1", "2", "3"],```

   ```["4", "5", "6"],```

   ```["7", " 8", "9"],```

   ```["10" , "11" , "12"]```

   ```]```


