![Screenshot of program running](https://github.com/agi-chan/facial-recognition/blob/main/screenshots/Screenshot%202024-09-04%20at%2015.50.36.png)

If main.py does not run, run mainedit.py!

Camera source can be changed by changing the number at the end of this function aka "cv.VideoCapture(0, 1, 2...)"

```
def run_recognition(self):
  video_capture = cv2.VideoCapture(1)
```
