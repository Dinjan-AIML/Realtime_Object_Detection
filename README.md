# Realtime Obejct Recognition

Realtime object recognition using the OpenCV +  MobileNetSSD caffemodel.


## Installation
All the dependencies can be installed using `pip`. Just use the following command from the root directory of the project.
```bash
pip3 install -r requirements.txt
```

**NOTE:** At the time of this writing, `public.py` is broken. If you have a problem installing it, check this [workaround here](https://github.com/C-Aniruddh/realtime_object_recognition/issues/1).

## How to run this script?

To run the script using webcam as source :

```bash
python3 real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --source webcam
```


Then to run the script using IP as source :

```bash
python3 real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --source web
```
