# Real-Time Object Detection with OpenCV and MobileNet-SSD

This project implements a **real-time object detection system** using the OpenCV DNN module and a pre-trained MobileNet SSD model (Caffe version). It processes video from a webcam, detects objects frame by frame, and generates annotated video outputs and detection reports.

---

##  Features

- Real-time object detection using MobileNet SSD
- Confidence-based filtering
- Bounding box annotations and FPS overlay
- Output detection video with optional display
- Logging to `.log` file and console
- Text summary report and CSV detection logs

---

## Model Used

- **Architecture**: MobileNet SSD (Single Shot Multibox Detector)
- **Framework**: Caffe
- **Files Needed**:
  - `deploy.prototxt.txt`
  - `mobilenet_iter_73000.caffemodel`

You can download these files from:
- [Caffe Model Zoo](https://github.com/chuanqi305/MobileNet-SSD)

---

##  Project Structure

Real-Time-Object-Detection/
- deploy.prototxt.txt - Model architecture configuration
- mobilenet_iter_73000.caffemodel - Pre-trained model weights
- Object_detection.log -  Execution log with timestamps
- detection_results/ - Output directory for results
     - detection_YYYYMMDD_HHMMSS.avi - Annotated video output
     - detection_summary.txt - Summary of detections and performance
     - detection_log.csv - Per-frame object detection log
- README.md - Project documentation
  
  ---
## Author
Twinkle Gupta

