OpenCV Attendance

For MacOS

Install opencv: brew install opencv

# Installation
```
pip3 install virtualenv
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```

Note: if you are using MacOS, make sure you use MacOS Terminal, otherwise you will not be able to access the camera.

To test camera, run:
```
python3 test_camera.py
```

To capture user face from 5 angles (top, down, left right, center), run:
```
python3 embeddings.py
```
Click on the camera screen and press s to save the picture.

To test facial recognition, run:
```
python3 recognition.py
```