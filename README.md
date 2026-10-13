# Indian Ambulance Number Plate Detection

## Project Overview
This project detects Indian ambulance number plates using a pretrained YOLOv8 model and extracts text using EasyOCR.

The system identifies number plate regions, extracts text, and filters possible Indian vehicle registration numbers using a regular expression.

## Technologies Used
- Python
- YOLOv8
- EasyOCR
- OpenCV
- Pandas
- Google Colab

## Project Workflow
1. Input ambulance images
2. Detect number plates using pretrained YOLOv8
3. Extract plate text using EasyOCR
4. Clean OCR text
5. Filter possible Indian number plates using pattern matching
6. Export results to CSV and Excel

## Project Results
- Total images processed: 529
- Images with at least one detection: 494
- OCR detection records: 734
- Preliminary regex matches: 18

**Note:** These are preliminary results. OCR text and regex matches require manual verification. 
Evaluation metrics are based on automatically generated pseudo-labels, not independently verified ground truth.

## Model
A pretrained YOLOv8 license plate detection model was used. No model training was performed as part of this project.

## Author
Prajakta Nawale
