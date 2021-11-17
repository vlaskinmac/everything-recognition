# Recognizing faces

This script is written as part of the task of the courses [Devman](https://dvmn.org).


- This code recognizes faces in the video stream. Using Haar cascades.
- The trained Haar cascades are located in the folder: `haarcascades` 
- For more information about Haar cascades, see here: [OpenCV Haar Cascades](https://www.pyimagesearch.com/2021/04/12/opencv-haar-cascades/)

<img src="https://user-images.githubusercontent.com/78322994/142227795-7f1b8d46-33b6-439a-b352-2e7577424a87.png" alt="drawing" width="200"/>  

### Python Version

Python 3.6 and later.

### Installing

To install the software, you need to install the dependency packages from the file: **requirements.txt**.

Perform the command:

```python
pip3 install -r requirements.txt

```

If the CV2 version from the file **requirements.txt** outdated, use the command:

```python
pip3 install opencv-python

```

## Parameters

- If you are using a webcam video, then the `video_capture` variable has a parameter `0` - by default.

- If you are using a file, the `video_capture` variable has a file path parameter.

- `scaleFactor=1.1` - The parameter sets the size of the image reduction.
- `minNeighbors=10` - The parameter sets the accuracy.
- `minSize=(30, 30)` - The parameter sets the minimum possible object size.

## Launch code

To run the program, use:

```python
$ python run.py 
```
To stop the program, use:

Сlick `q`





## Authors

**vlaskinmac**  - [GitHub-vlaskinmac](https://github.com/vlaskinmac/)


