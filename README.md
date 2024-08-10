# One-Object-Tracking-using-OpenCV
This project demonstrates object tracking using various algorithms available in OpenCV, including CSRT, KCF, Boosting, MIL, TLD, MedianFlow, and MOSSE. The example video used is `kora.mp4`, and the tracker chosen for this example is CSRT.

# Object Tracking using OpenCV

This project demonstrates object tracking using various algorithms available in OpenCV, including CSRT, KCF, Boosting, MIL, TLD, MedianFlow, and MOSSE. The example video used is `kora.mp4`, and the tracker chosen for this example is CSRT.

## Setup

1. Ensure that you have Python installed along with the required libraries (`opencv-python`, `imutils`).
2. Place the video file `messi_.mp4` in the appropriate directory.

## Usage

1. Clone the repository.
2. Open the Jupyter Notebook `Object_Tracking.ipynb`.
3. Run the notebook step by step to see the object tracking in action.

## Steps

- **Select a Tracker**: The tracker can be chosen from the predefined dictionary.
- **Load the Video**: Load the video where the object needs to be tracked.
- **Select the ROI**: Manually select the region of interest (ROI) in the first frame of the video.
  ![image](https://github.com/user-attachments/assets/f3f6b3ea-5ceb-4100-8ba4-dcc9f0924825)

- **Track the Object**: The object will be tracked across subsequent frames.

## License

This project is open-source and available under the MIT License.
