# Detection of Tampered PAN Cards by Computer Vision
This code repository contains a Python script for detecting tampered PAN (Permanent Account Number) cards using computer vision techniques. The script compares the similarity between the provided PAN card image and an original PAN card image to identify any alterations or tampering.

## How It Works
The script utilizes the following steps to detect tampered PAN cards:

### Image Loading: 
The script downloads the provided PAN card image and the original PAN card image from URLs.
### Image Preprocessing: 
Preprocessing techniques are applied to enhance the quality of the images and prepare them for comparison.
### Feature Extraction: 
Computer vision techniques are employed to extract relevant features from both images.
#### Similarity Comparison:
The structural similarity score between the provided PAN card image and the original PAN card image is calculated.
### Tampering Detection: 
Based on the similarity score, the script determines whether the provided PAN card image has been tampered with.
### Required Libraries
To run the script, ensure you have the following libraries installed:


**To install these libraries, you can use pip:**

```bash
pip install scikit-image imutils opencv-python-headless Pillow request
