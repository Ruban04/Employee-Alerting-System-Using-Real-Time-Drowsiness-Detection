# Employee Drowsiness Detection System

This system monitors employees in real-time to detect signs of drowsiness and alerts them when necessary.

## Features
- Real-time face detection
- Eye tracking and blink detection
- Drowsiness detection based on eye aspect ratio
- Audio alerts when drowsiness is detected
- Logging of drowsiness events

## Setup Instructions

1. Install Python 3.8 or higher
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the facial landmark predictor:
   ```bash
   # The system will automatically download the required model on first run
   ```

## Usage

Run the main application:
```bash
python main.py
```

## Configuration

You can adjust the following parameters in the code:
- Drowsiness threshold
- Alert frequency
- Camera settings

## Requirements
- Webcam
- Python 3.8+
- Required Python packages (see requirements.txt) 