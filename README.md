# AI-Coach-Project

## AI Squat Analysis System

### Project Category
**Object Tracking (Human Pose Tracking using AI)**

---

## Project Idea

AI Squat Analysis System is an AI-powered application that analyzes squat exercises using computer vision and human pose estimation. The system tracks body joints in real time, counts squat repetitions, evaluates exercise technique, and provides instant feedback to help users improve performance and reduce the risk of injuries.

---

## Features

- Real-time human pose detection and tracking
- Automatic squat repetition counting
- Knee angle calculation
- Technique evaluation (Good / Bad / Risk)
- AI-based feedback system
- Processed video with skeleton overlay
- Performance scoring for each repetition
- Works on Google Colab

---

## Technologies Used

- Python
- OpenCV
- TensorFlow
- TensorFlow Hub (MoveNet)
- NumPy
- Pandas
- Google Colab

---

## System Workflow

1. Load the input video.
2. Detect body keypoints using MoveNet.
3. Track body joints frame by frame.
4. Calculate knee angles.
5. Detect squat movement.
6. Count repetitions.
7. Evaluate squat quality.
8. Generate the output video with analysis.

---

## System Output

The system provides:

- Processed video with skeleton overlay
- Squat repetition counter
- Knee angle tracking
- Technique evaluation
- Performance score for each repetition
- Real-time movement analysis

---
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ac8fdb8d-24e0-4b68-96af-2d812cdb0be2" />


## Project Structure

```
AI-Coach-Project/
│
├── README.md
├── requirements.txt
├── AI_Squat_Analysis.ipynb
├── input/
│   └── input_video.mp4
├── output/
│   ├── output.mp4
│   └── report.csv
├── images/
│   ├── screenshot1.png
│   └── screenshot2.png
└── LICENSE

---
## OpenCV Usage in the Project

This project uses **OpenCV** as the main computer vision library for processing video frames and displaying real-time analysis. OpenCV is integrated with the MoveNet pose estimation model to perform human pose tracking and squat analysis.

### How OpenCV is Used

- Read the input video using `cv2.VideoCapture()`.
- Process each video frame individually.
- Draw body keypoints (hip, knee, and ankle) using `cv2.circle()`.
- Connect body joints with lines using `cv2.line()`.
- Display real-time information such as:
  - Squat repetition counter
  - Knee angle
  - Exercise status
- Generate and save the processed output video with all visual annotations.

### Object Tracking

The project performs **Human Pose Tracking**, which is a type of **Object Tracking**. Instead of tracking a simple object such as a ball or a car, the system tracks the human body joints frame by frame using MoveNet and OpenCV. The tracked keypoints are then used to calculate knee angles, detect squat movements, count repetitions, and evaluate exercise quality.

### OpenCV Functions Used

- `cv2.VideoCapture()`
- `cv2.circle()`
- `cv2.line()`
- `cv2.putText()`
- OpenCV frame processing
- Video output generation using OpenCV with FFmpeg

### Conclusion

OpenCV is responsible for video processing, frame handling, drawing body landmarks, displaying analysis results, and generating the final analyzed video. Combined with MoveNet, it enables accurate human pose tracking and real-time squat analysis.

## Requirements

Install the required libraries:

```bash
pip install opencv-python tensorflow tensorflow-hub numpy pandas
```

---

## How to Run

1. Open the project in Google Colab.
2. Install the required libraries.
3. Upload the input video.
4. Run all notebook cells.
5. Download the analyzed output video.

---

## Applications

- Fitness coaching
- Home workout monitoring
- Sports performance analysis
- Injury prevention
- AI-based exercise evaluation

---

## Final Summary

The AI Squat Analysis System uses computer vision and AI pose estimation to track human body movement during squat exercises. It automatically counts repetitions, evaluates exercise quality, measures knee angles, and provides real-time feedback to improve workout performance and reduce injury risk.

---

