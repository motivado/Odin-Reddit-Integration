# Odin AI - Biomechanical Analysis Bot

## Project Overview
Odin is a computer vision application designed to assist weightlifting athletes by analyzing video kinematics. The project uses a Python backend with OpenCV to track barbell velocity and trajectory.

## Reddit Integration
This module is designed to interact with the Reddit API via PRAW to allow for:
1.  **Authenticated Uploads:** Securely uploading processed videos to r/formcheck or r/weightlifting.
2.  **Human-in-the-Loop:** All uploads are triggered manually by an operator after reviewing the computer vision analysis.

## Technology Stack
* **Language:** Python 3.10+
* **Computer Vision:** OpenCV, NumPy
* **Reddit API:** PRAW (Python Reddit API Wrapper)
* **Interface:** Telegram Bot API

## Privacy & Security
The source code containing the core computer vision algorithms is proprietary and hosted in a private repository. The Reddit integration follows all API terms of service, specifically regarding rate limits and user privacy.
