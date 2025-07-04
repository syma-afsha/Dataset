
# Sim2Real Domain Randomization for Object Tracking in Robotics Applications

This repository contains the synthetic datasets and tracking models used in the paper **"Sim2Real Domain Randomization for Object Tracking in Robotics Applications: A Transfer Learning Approach"**. The work aims to bridge the sim2real reality gap in object tracking by generating scalable synthetic datasets using domain randomization techniques, training detection-based and segmentation-based trackers, and evaluating them under real-world conditions.

## Dataset

The dataset consists of 2,592 frames and 22,654 annotations, specifically designed for evaluating object tracking algorithms using standard Multi-Object Tracking (MOT) metrics such as MOTA, MOTP, and IDF1.

### Video Sequences:
- **Video 1**: 1,426 frames, 40 objects, 13,959 annotations, 5 classes
- **Video 2**: 1,166 frames, 58 objects, 8,695 annotations, 5 classes

This dataset contains a variety of challenges such as motion blur, occlusion, and varying lighting conditions. It has been annotated with subpixel spatial precision and is structured to evaluate tracking performance under real-world variability.

## Files
- **gt.mp4**, **gt2.mp4** : Sample video files used for testing the tracking models.
- **gt.txt**, **gt2.txt**: Annotation files for the corresponding frames.
- **.gitattributes**: File for tracking large files using Git LFS.



