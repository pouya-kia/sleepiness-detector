# Sleepiness Detector

A real-time sleepiness detection application using a laptop camera. This program monitors eye movements to detect drowsiness by calculating the Eye Aspect Ratio (EAR). If the user shows signs of drowsiness, the program displays a "Sleepiness Detected" warning on the screen.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)

## Features
- Real-time drowsiness detection using a camera feed.
- Uses Eye Aspect Ratio (EAR) to detect closed eyes, indicating possible sleepiness.
- Alerts the user on-screen when sleepiness is detected.

## Requirements
- Python 3.7+
- OpenCV
- MediaPipe
- Scipy

All dependencies are listed in `requirements.txt`.

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/sleepiness-detector.git
   cd sleepiness-detector
