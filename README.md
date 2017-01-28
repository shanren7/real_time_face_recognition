# real_time_face_detection and recognition
This is a real time face detection and recognition project base  on opencv/tensorflow/mtcnn/facenet. An chinese version of description is [here](https://zhuanlan.zhihu.com/p/25025596) .

##Structure
![](https://github.com/shanren7/real_time_face_recognition/blob/master/images/real%20time%20face%20detection%20and%20recognition.jpg)

##Inspiration
The code was inspired by several projects as follows:

1.[OpenFace](https://github.com/cmusatyalab/openface). The main idea was inspired by openface. However, I prefer python and tensorflow,so there comes this project.

2.[davidsandberg/facenet](https://github.com/davidsandberg/facenet).

   facenet.py was taken from https://github.com/davidsandberg/facenet/blob/master/facenet/src/facenet.py
    
   nn4.py was taken from https://github.com/davidsandberg/facenet/blob/master/src/models/nn4.py
    
   detect_face.py was taken from https://github.com/davidsandberg/facenet/blob/master/src/align/detect_face.py
    
3.[yobibyte/yobiface](https://github.com/yobibyte/yobiface).

##Dependencies
1.tensorflow
2.opencv with python bindings (cv2)
3.jupyter notebook for running .ipynb examples

##Running
1.Downloading pre-trained facenet from https://github.com/yobibyte/yobiface/blob/master/model/model-20160506.ckpt-500000 and putting in model_check_point folder.

2.Running [real time face detection and recognition.ipynb](https://github.com/shanren7/real_time_face_recognition/blob/master/real%20time%20face%20detection%20and%20%20recognition.ipynb) with jupyter notebook

##Results
![](https://github.com/shanren7/real_time_face_recognition/blob/master/images/video_guai_20.jpg)
![](https://github.com/shanren7/real_time_face_recognition/blob/master/images/video_guai_2192.jpg)
