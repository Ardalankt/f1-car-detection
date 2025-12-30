# F1 Car Detection using YOLOv8

This project uses **YOLOv8** to detect Formula 1 cars from four teams: **Ferrari, McLaren, Red Bull, and Mercedes**. The model is trained on a custom dataset hosted on Roboflow and can perform detection on both images and videos.

## Dataset

The dataset is available on Roboflow: [Formula One Car Detection Dataset](https://universe.roboflow.com/jayanths-workspace/formula-one-car-detection).

This dataset contains annotated images of F1 cars from the four teams from mainly the 2021 season.

## Before & After Detection

Prediction of the base model:

![Uploading Screenshot 2025-12-30 at 15.41.56.png…]()
![Uploading Screenshot 2025-12-30 at 15.42.35.png…]()
![Uploading Screenshot 2025-12-30 at 15.42.44.png…]()

Prediction of the trained model:

![Uploading Screenshot 2025-12-30 at 15.29.17.png…]()
![Uploading Screenshot 2025-12-30 at 15.30.37.png…]()


## Results

- The model detects multiple cars in crowded scenes relatively accurately
- Bounding boxes are labeled with team names
- Real-time video detection is supported

## Notes

- Input images and videos can be of varying resolution
- The model is robust to different camera angles and lighting conditions
