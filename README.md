# YoloV3_FromScrach_LiveCam

yolov3.py ==> reads config file which is yolov3.cfg for creating the yoloV3 model.
convert_weights.py ==> puts weights in yolov3.weights file to model.
utils.py ==> drwas, creates boxes and reads yolov3 model output.
liveCamYoloV3.py ==> uses opencv for getting live video from webcam and uses yolov3 on the webcam inputs. Uses utils file to draw boxes on them...
