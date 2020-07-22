# webcam-live-face-detector-through-OpenCV
This project is purely built in python language recently. The main tasks it will done is to detect human faces from videos or images.

It can also work directly with webcam.

'Requirements.txt' file contains packages with versions info. required to run the code.

Run 'webcam.py' for face detection using webcam, you can also use this file to detect faces in video by entering video-path instead of '0' in cv2.VideoCapture method, for example:

						cv2.VideoCapture("../video/path/1.mp4")
							
To count number of faces with face detection run 'face_detect.py'.

Face detection from image could also be done by running "python live.py", but before running set image path in 'live.py'.
