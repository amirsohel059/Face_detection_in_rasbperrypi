# Face Detection on Raspberry Pi

This project captures images from a Raspberry Pi camera and detects faces using OpenCV's Haar Cascade classifier. Detected faces are saved as separate image files in a directory.

## Prerequisites

1. **Raspberry Pi** with Raspberry Pi OS installed.
2. **Raspberry Pi Camera Module** connected and enabled.
3. Python 3 installed on the Raspberry Pi.
4. Opencv installed if not you can refer to the [OpenCV installation guide for Raspberry Pi](https://qengineering.eu/install-opencv-on-raspberry-64-os.html).


## Installation

1. **Clone this repository** (if hosted on a platform like GitHub):
    ```bash
    git clone https://github.com/amirsohel059/Face_detection_in_rasbperrypi.git
    cd .\Face_detection_in_rasbperrypi\
    ```

2. **Install dependencies** using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the Python script:

```bash
python3 face_detection.py
