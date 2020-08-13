## Face Detection 
### Using Caffe Model:

The model is shipped in the OpenCV, DNN model for face detector sample
[Link](https://github.com/opencv/opencv_3rdparty/blob/dnn_samples_face_detector_20170830/res10_300x300_ssd_iter_140000.caffemodel)

To run the script:
```python detect_faces.py --image <image-path> --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
```