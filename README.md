# Crime-Detector


## Overview
This project is a real-time violence detection system using Computer Vision and Deep Learning techniques. It processes live camera input to detect and alert any incidents of violence with high accuracy.

## Features
- Real-time violence detection from live camera feeds
- Web-based monitoring interface
- High accuracy (87%) in detecting violent incidents
- Scalable architecture for multiple camera inputs

## Technologies Used
- Python
- TensorFlow
- Keras
- OpenCV
- Django
- VGG16 (for transfer learning)
- LSTM (for sequence analysis)

## Project Structure
1. Deep Learning Model:
   - Utilizes TensorFlow and Keras
   - Implements transfer learning with VGG16
   - Uses LSTM for analyzing video sequences
2. Video Processing:
   - OpenCV for frame extraction and preprocessing
3. Web Application:
   - Django-based interface for live monitoring
   - Real-time display of detection results

## Model Architecture
- Transfer Learning: VGG16 pre-trained on ImageNet
- Sequence Analysis: LSTM layer for temporal features
- Output: Binary classification (Violent/Non-violent)

## Performance
- Current model accuracy: 87%
- Real-time processing capability

## Future Improvements
- Enhance model accuracy through fine-tuning

## Contributing
- Riddhish Thakare
- Jainum Sanghavi
