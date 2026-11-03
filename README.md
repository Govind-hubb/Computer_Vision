# CCA 3 - Computer Vision Practical Assignment

## Project Overview

This project implements practical computer vision techniques from Units 3, 4 and 5 using Python and OpenCV.

The project covers image restoration, morphological processing, segmentation, feature extraction, object recognition and video motion estimation.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- scikit-image
- Pandas
- Ultralytics YOLO
- Jupyter Notebook

## Project Structure

```text
CCA3-Computer-Vision/
│
├── dataset/
│   ├── images/
│   │   ├── original.jpg
│   │   └── second_photo.jpg
│   │
│   └── videos/
│       └── motion_video.mp4
│
├── unit3-image-restoration/
├── unit4-feature-extraction/
├── unit5-object-recognition/
├── unit5-motion-estimation/
│
├── outputs/
├── documentation/
├── requirements.txt
└── README.md
```

## Experiments

### Unit 3: Image Restoration and Segmentation
- Gaussian noise and salt-and-pepper noise
- Gaussian and median filtering
- PSNR and SSIM evaluation
- Image thresholding
- Erosion, dilation, opening and closing
- Canny edge detection
- Watershed segmentation

### Unit 4: Feature Extraction and Matching
- Histogram of Oriented Gradients (HOG)
- SIFT keypoint detection
- SIFT descriptor extraction
- Feature matching
- Rotation and resizing comparison

### Unit 5: Object Recognition
- Haar Cascade face detection
- YOLO object detection
- Detection comparison

### Unit 5: Motion Estimation
- Frame differencing
- MOG2 background subtraction
- Lucas-Kanade optical flow

## Installation and Execution

1. Install Python.
2. Open the project folder in VS Code.
3. Create and activate the virtual environment.
4. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

5. Open the relevant Jupyter Notebook.
6. Select the project virtual environment as the notebook kernel.
7. Execute the notebook cells in order.

## Dataset Instructions

Place the original photograph inside:

`dataset/images/`

Place the second photograph inside:

`dataset/images/`

Place the original self-recorded video inside:

`dataset/videos/`

Update notebook file paths if filenames differ.

## Results

The project generates visual outputs, comparison tables, feature visualizations, object detection results and motion estimation results.

## Conclusion

This assignment demonstrates the implementation and comparison of several computer vision techniques using Python and OpenCV.

The experiments show how images can be restored and segmented, how features can be extracted and matched, how objects can be detected, and how motion can be analyzed in video.

## Author

**Student:** Govind Thakur  
**Assignment:** CCA 3 - Computer Vision  
**Units:** 3, 4 and 5