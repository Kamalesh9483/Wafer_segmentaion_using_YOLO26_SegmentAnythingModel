# Wafer_segmentaion_using_YOLO26_SegmentAnythingModel

##Silicon Wafer Defect Detection & Segmentation
###YOLOv26 + SAM (Segment Anything Model)

Overview
1. This Project demonstrates an end-to-end computer vision pipeline for silicon wafer image analysis, combining:
2. Object detection using a custom-trained YOLOv26 model
3. High-precision segmentation using Meta’s Segment Anything Model (SAM)
4. Clear visualization of original images vs segmented outputs

The workflow starts from bounding-box labeling, progresses through YOLO training, and finally performs YOLO-guided SAM segmentation.

Dataset:
Source: Roboflow Universe
https://universe.roboflow.com/test-c3vhv/silicon-wafer-icwiy

<img width="1220" height="2612" alt="image" src="https://github.com/user-attachments/assets/b05283f5-ba89-4b55-946f-495084d6fe8a" />

Results:
<img width="1582" height="812" alt="Image_segmentation_3" src="https://github.com/user-attachments/assets/7ccffe0e-0fcd-4bd2-ae8d-1d9d3229ddc0" />
<img width="1582" height="812" alt="Image_segmentation_1" src="https://github.com/user-attachments/assets/4435af6a-fcf3-43fe-989f-ca97613f32eb" />
<img width="1440" height="790" alt="Image_segmentation_2" src="https://github.com/user-attachments/assets/a908a81b-4200-4b27-a61a-2204dd313904" />
