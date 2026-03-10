# Land Use Classification – Building & Road Mapping

## Project Overview
This project uses Python and OpenCV to classify satellite or aerial images into different land use categories such as:

- Buildings
- Roads
- Vegetation
- Water

The system performs image segmentation using color-based classification in HSV color space and calculates the percentage area occupied by each class.

## Aim
To analyze aerial or satellite imagery and identify land use categories automatically using image processing techniques.

## Objectives
- Load and process a satellite image
- Segment the image into land cover classes
- Calculate the area percentage of each class
- Display classification masks and results

## Tools and Technologies
- Python
- OpenCV
- NumPy
- Matplotlib

## Project Files
- `landuse.py` → main Python code
- `satellite_image.jpg` → input image
- `requirements.txt` → required libraries

## Installation
Install the required libraries using:

```bash
pip install -r requirements.txt
