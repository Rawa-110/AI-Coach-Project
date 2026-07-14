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

## Project Structure

```
AI-Coach-Project/
│
├── notebooks/
│   └── AI_Squat_Analysis.ipynb
│
├── input/
│   └── input_video.mp4
│
├── output/
│   └── analyzed_video.mp4
│
├── images/
│   ├── screenshot1.png
│   └── screenshot2.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

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

