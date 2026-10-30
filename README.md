# AI-Based Football Player and Ball Detection & Tracking Using YOLOv26

Detects and tracks **football (soccer) players and the ball** in match video using the YOLOv26 object detection model.

The full workflow lives in a single notebook, and a sample of the model's output on video is included in the repo.

---

## Demo

The file [`Inference Output.avi`](Inference%20Output.avi) shows the model's detections and tracking on a sample clip.

<img width="1153" height="648" alt="Screenshot (268)" src="https://github.com/user-attachments/assets/dedd2a8a-07ad-4860-a7be-531d52d5d6f0" />

<img width="790" height="790" alt="3bb34027-5c2d-4d32-a60d-d8b25dab7f0a" src="https://github.com/user-attachments/assets/7b95eb46-dc34-422f-ac12-c651f53441fb" />

---

## What this project does

- **Detection:** locates players and the ball in each video frame
- **Tracking:** keeps a consistent identity for each detected object across frames
- **Output:** an annotated video with boxes and track IDs
---

## Dataset

> Describe the dataset here: name and source, number of images/frames, classes, annotation format, and the train/validation/test split.

## Model and training

> Fill in from your notebook:
>
> | Setting | Value |
> |---|---|
> | Base model | YOLOv26 variant (e.g. n / s / m) |
> | Epochs | |
> | Image size | |
> | Batch size | |
> | Optimizer / learning rate | |
> | Hardware | |

## Results

<img width="2400" height="1200" alt="results (2)" src="https://github.com/user-attachments/assets/da3ebe81-6571-4fee-97dc-646ff578f101" />

| Class | Precision | Recall | mAP@0.5 | mAP@0.5:0.95 |
|---|---|---|---|---|
| Player | | | | |
| Ball | | | | |

---

## Repository contents

| File | Description |
|---|---|
| `AI-Based Football Player and Ball Detection & Tracking.ipynb` | Notebook with the full detection and tracking workflow |
| `Inference Output.avi` | Sample output video with detections and tracks |
| `README.md` | This file |

---

## Limitations and future work

- Small, fast-moving objects like the ball are harder to detect, especially when blurred or occluded
- Players can swap or lose IDs when they cross or are occluded
- Possible extensions: team classification by jersey color, player speed and distance, ball possession, and heatmaps

## Citation and acknowledgements

- Built on [Ultralytics](https://github.com/ultralytics/ultralytics)


## Author

**Alaa Awad**
