# EORA-task--eye-blink-detection

To use this application you need shape_predictor_68_face_landmarks.dat
( https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat )

To use with stream video:
python detect_blinks.py -p shape_predictor_68_face_landmarks.dat
To use with video file:
python detect_blinks.py -p shape_predictor_68_face_landmarks.dat -v blink_detection_demo.mp4

To turn off application press "q"
