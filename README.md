# mcta4364-yolov10-conveyor-sorting
MCTA 4364 Machine Vision
Project Title: Real-Time Vision-Based Simulated Conveyor Sorting System Using YOLOv10
## Team Members:
1) QASHRINA AISYA BINTI MOHD NAZARUDIN (2315184)
2) ALYA KHAIRAH BINTI KHAIRUL JAMIL (2317100)
3) NUREL HUMAIRAH BINTI MUHAMMAD FIRDAUS (2315680 ) 

## Track 2(Paper)   
Source Link (PDF): https://arxiv.org/abs/2405.14458
​GitHub Link: https://github.com/THU-MIG/yolov10




## Project Overview
This project develops a real-time vision-based object detection pipeline using **YOLOv10-N** to classify moving items on a simulated conveyor belt into four target categories: `plastic`, `glass`, `metal`, and `anomaly`. In Weeks 9–14, this baseline detector will be integrated with multi-object tracking (ByteTrack) and an OpenCV virtual sorting gate.

## System Architecture
![System Pipeline Diagram](assets/pipeline_diagram.png)

## Repository Structure
```text
├── assets/                  # System pipeline diagram & report figures
├── notebooks/
│   ├── 01_dataset_eda.ipynb       # Dataset exploration & class distribution (Person B)
│   └── 02_yolov10_baseline.ipynb  # YOLOv10-N training & validation on Colab T4 (Person C)
├── .gitignore
├── README.md
└── requirements.txt
