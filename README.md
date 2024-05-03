```markdown
# Live Face Detection using OpenCV

This is a simple Python script for detecting faces in live video streams using OpenCV.

## Installation

1. Make sure you have Python installed on your system.
2. Install OpenCV library using pip:

```bash
pip install opencv-python
```

## Usage

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd <project_directory>
```

3. Run the script:

```bash
python detect_faces_live.py
```

4. Press 'q' to exit the live detection.

## How it works

This script uses the pre-trained face cascade classifier provided by OpenCV to detect faces in real-time video streams. It opens the default camera (usually camera 0) and continuously captures frames. Each frame is converted to grayscale, and then faces are detected using the `detectMultiScale` method. Bounding boxes are drawn around the detected faces. If more than one face is detected, a warning message is displayed. Press 'q' to exit the program.

## Dependencies

- Python 3.x
- OpenCV

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
```
