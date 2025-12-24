# Hand Gesture Volume Control

A Python application that uses hand gestures to control your system volume through your webcam. Control the volume by adjusting the distance between your thumb and index finger!

## Features

- Real-time hand tracking using MediaPipe
- Volume control based on finger distance
- Visual feedback with landmark tracking
- Simple and intuitive gesture control

## How It Works

The application tracks your hand using your webcam and measures the distance between your thumb tip (landmark 4) and index finger tip (landmark 8). 

- **Increase Volume**: Move your thumb and index finger apart (distance > 25 units)
- **Decrease Volume**: Bring your thumb and index finger closer together (distance ≤ 25 units)

## Requirements

```
opencv-python
mediapipe
pyautogui
```

## Installation

1. Clone this repository or download the script

2. Install the required dependencies:
```bash
pip install opencv-python mediapipe pyautogui
```

## Usage

1. Run the script:
```bash
python volume_control_python.py
```

2. Position your hand in front of the webcam

3. Adjust the distance between your thumb and index finger to control volume:
   - **Spread fingers apart** → Volume Up
   - **Bring fingers together** → Volume Down

4. Press `ESC` to exit the application

## Visual Indicators

- **Yellow circle**: Index finger tip
- **Red circle**: Thumb tip
- **Green line**: Connection between thumb and index finger showing the distance

## Notes

- Ensure your webcam is properly connected and accessible
- Good lighting conditions improve hand detection accuracy
- The application uses your system's volume up/down keys, so it should work across different operating systems
- Press `ESC` key to close the application

## Troubleshooting

- **Webcam not detected**: Make sure no other application is using the webcam
- **Hand not detected**: Ensure proper lighting and that your hand is clearly visible
- **Volume not changing**: Check your system's keyboard shortcut settings for volume control

## Author

**RAJA R**
- Website: [https://rajar219.github.io/bio/](https://rajar219.github.io/bio/)
- Email: leviraja670@gmail.com

## License

Feel free to use and modify this code for your projects!
