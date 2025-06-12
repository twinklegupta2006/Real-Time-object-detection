#  Real-Time Object Detection Using OpenCV and MobileNet SSD

## Overview  
This project performs **real-time object detection** using a **pre-trained MobileNet SSD model** with **OpenCV's DNN module**. It captures live webcam video, detects objects, labels them, counts each object type per frame, and saves the annotated video.

## Features
-  Detects 20+ object classes in real-time  
-  Highlights and labels detected objects  
-  Displays object counts live  
-  Saves annotated video automatically (`output.avi`)  
-  Automatically plays the saved video after recording

## Requirements

Install dependencies using pip:

> Python version: 3.6 or higher
## File Structure  

real-time-object-detection/
│
├── object_detection.ipynb # Jupyter Notebook with full code
├── deploy.prototxt # Model architecture
├── mobilenet_iter_73000.caffemodel # Pre-trained weights
├── output.avi # Saved output video
├── README.md # Project documentation

## How to Run  

1. Open `object_detection.ipynb` in **Jupyter Notebook**.
2. Run all cells in order.
3. The webcam will start and detect objects in real-time.
4. After processing 300 frames (or pressing `q`), the video is saved and opened automatically.

##  Model Info  

- **Architecture**: MobileNet SSD  
- **Training Data**: Pascal VOC  
- **Object Classes**:
  `aeroplane, bicycle, bird, boat, bottle, bus, car, cat, chair, cow, diningtable, dog, horse, motorbike, person, pottedplant, sheep, sofa, train, tvmonitor`

## Future Improvements  
- GUI button to play saved video  
- Frame-level object logs  
- Option to upload a custom video file instead of using a webcam


## Author  
**Twinkle Gupta**  
GitHub: [@twinklegupta2006](https://github.com/twinklegupta2006)


