<h2> Tennis Analysis with YOLO and Key Point Extraction </h2>

📋 Project Overview
This project aims to develop an AI-based system to analyze tennis matches using YOLO, PyTorch, and Key Point Extraction algorithms. By automating the detection and tracking of players, the ball, and key court points, we enable coaches and athletes to gain deeper insights into performance and strategies.

🎯 Problem Statement
Traditional tennis performance analysis relies on manual video reviews, which are time-consuming and often inaccurate. Players and coaches need:
- Accurate average shot speed data.
- Precise ball drop position analysis.
- Comparisons with other players for competitive benchmarking.

✅ Proposed Solution
We propose a system that:
- Detects players and tennis balls in real-time using YOLO.
- Extracts court key points using a CNN model.
- Tracks ball trajectories and calculates shot speeds.
- Provides visual and statistical reports to support data-driven coaching.

🗂️ Dataset
- Player & Ball Dataset: Videos with bounding box annotations for players and balls (from open sources like Roboflow).
- Court Dataset: Annotated images of tennis courts with lines and key points.

⚙️ Tech Stack
- Object Detection: YOLO (You Only Look Once)
- Key Point Extraction: CNNs with PyTorch
- Framework: PyTorch for model training and inference

🔑 Model Workflow
- Preprocessing: Data augmentation (rotation, zoom, brightness adjustments).
- Training: YOLO and CNN models trained with optimized hyperparameters.
- Feature Extraction: Track ball and player movements across video frames.
- Post-Processing: Apply Non-Maximum Suppression (NMS) to refine bounding boxes.
- Evaluation: Use precision, recall, and mAP to measure performance.

📊 Expected Outcomes
- Accurate detection and tracking of players and balls.
- Visualized ball trajectories and calculated shot speeds.
- Actionable performance insights for players and coaches.
- Enhanced training strategies and data-backed decisions.

👥 Authors
- Mikha Aldyn Yauw
- Martin Emmanuel Chang
- Pixel Ariel Christopher

📌 Notes
This is part of our Ilmu Data II project, focusing on leveraging modern AI techniques for sports analytics, specifically tennis.
