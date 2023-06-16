# Bangkit Capstone C23-PS298 Machine Learning Repositories🥷
Hi folks👋
This repo contains our Machine Learning Training and Dataset that runs on [Google Colab](https://colab.research.google.com/?utm_source=scs-index)

## Library used🧩
- ✅[Yolov8 Ultralytics](https://docs.ultralytics.com/) - used as the chosen framework for the object detection model.
- ✅[Python](https://www.python.org/downloads/) - used for utilized for coding the object detection system.
- ✅[Numpy](https://numpy.org/install/) - used to perform a wide variety of mathematical operations on arrays.
- ✅[Tensorflow](https://www.tensorflow.org/install) - used as the underlying deep learning library.



## Process Flow of Object Detection Development🔃
![SaBo smart border security system](https://github.com/C23-PS298/machine-learning/assets/77234852/71e3a80d-ec32-40b1-a1cf-83b73b6e436d)

The object detection flowchart begins with data acquisition and dataset creation. If videos are available, frames are extracted. Otherwise, captured frames/images are used directly. The YOLOv8 model detects objects in the frames/images and converts dataset annotations to a compatible format. The model is then trained to improve object detection. Detected objects are marked with bounding boxes during frame/image processing, and annotated frames/images are merged to generate the final video output. The flowchart concludes with the completion of the object detection process and video output generation.
