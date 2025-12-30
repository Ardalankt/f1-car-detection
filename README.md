# F1 Car Detection using YOLOv8

This project uses **YOLOv8** to detect Formula 1 cars from four teams: **Ferrari, McLaren, Red Bull, and Mercedes**. The model is trained on a custom dataset hosted on Roboflow and can perform detection on both images and videos.

## Dataset

The dataset is available on Roboflow: [Formula One Car Detection Dataset](https://universe.roboflow.com/jayanths-workspace/formula-one-car-detection).

This dataset contains annotated images of F1 cars from the four teams from mainly the 2021 season.

## Before & After Detection

Prediction of the base model:

![before](path/to/original_image.jpg)

Prediction of the trained model:

![after](path/to/detected_image.jpg)

## Results

- The model detects multiple cars in crowded scenes relatively accurately
- Bounding boxes are labeled with team names
- Real-time video detection is supported

## Notes

- Input images and videos can be of varying resolution
- The model is robust to different camera angles and lighting conditions
