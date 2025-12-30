# F1 Car Detection using YOLOv8

This project uses **YOLOv8** to detect Formula 1 cars from four teams: **Ferrari, McLaren, Red Bull, and Mercedes**. The model is trained on a custom dataset hosted on Roboflow and can perform detection on both images and videos.

## Dataset

The dataset is available on Roboflow: [Formula One Car Detection Dataset](https://universe.roboflow.com/jayanths-workspace/formula-one-car-detection).

This dataset contains annotated images of F1 cars from the four teams from mainly the 2021 season.

# Before & After Detection

## Prediction of the base model:

<img width="1440" height="900" alt="Screenshot 2025-12-30 at 15 41 56" src="https://github.com/user-attachments/assets/96659601-6761-497e-8ada-db53ece93dd2" />

<img width="1440" height="900" alt="Screenshot 2025-12-30 at 15 42 35" src="https://github.com/user-attachments/assets/8f3645a7-3fad-4fd6-83b0-7c4eac5a6a06" />

<img width="1440" height="900" alt="Screenshot 2025-12-30 at 15 42 44" src="https://github.com/user-attachments/assets/7c58c398-0d79-4ec3-8871-9d1fcd4de87a" />

## Prediction of the trained model:

<img width="1440" height="900" alt="Screenshot 2025-12-30 at 16 58 15" src="https://github.com/user-attachments/assets/9c74b9c7-ffbe-4280-b6e9-ade0f5f3b734" />

<img width="1440" height="900" alt="Screenshot 2025-12-30 at 15 30 37" src="https://github.com/user-attachments/assets/afd3d8b0-d688-4c38-95a9-5cf12b8e8d7f" />

## Results

- The model detects multiple cars in crowded scenes relatively accurately
- Bounding boxes are labeled with team names
- Real-time video detection is supported

## Notes

- Input images and videos can be of varying resolution
- The model is robust to different camera angles and lighting conditions
