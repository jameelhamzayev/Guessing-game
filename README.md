# Teknofest 2022 Baku Metaverse team


```
import cv2

# Open your computer's default camera device.

camera = cv2.VideoCapture(0)

# while loop to read the camera image
while True:
    success, img = camera.read() 
    if success:
        cv2.imshow('Video', img)
    #if you pressed "q" key it'll break the loop
    k = cv2.waitKey(1)
    if k == ord('q'):
        break

# release your camera device and close the OpenCV windows
camera.release()
cv2.destroyAllWindows()
```



