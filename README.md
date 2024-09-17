# VehiCount
VehiCount is a Python-based project that uses the YOLOv8 model for real-time vehicle detection and the SORT (Simple Online and Realtime Tracking) algorithm for tracking objects across frames in a video stream.

## Features:

- YOLOv8 Object Detection: Detects vehicles in real-time using the YOLOv8 pre-trained model.
- SORT Tracking: Tracks detected vehicles across video frames to maintain accurate counting.
- Vehicle Counting: Counts the number of vehicles passing through a designated region.
- Masking Regions of Interest: Ability to define specific areas in the frame for detection by applying masks.
- Overlay Graphics: Adds custom graphic overlays to the video for enhanced visualization.
- Thresholding for Confidence Levels: Only counts objects with a detection confidence above a threshold.


## How It Works:
- Object Detection: The YOLOv8 model detects objects in the video, specifically looking for vehicles such as cars, trucks, buses, and motorbikes.
- Tracking: SORT tracks these vehicles across frames, assigning unique IDs to each detected object.
- Counting: When a vehicle crosses a predefined line in the video frame (region of interest), it is counted.
- Masking: A mask can be applied to focus detection on a specific region of the video.
- Graphics Overlay: Custom graphics can be overlaid on the video to show important metrics, like vehicle count.


