# SigniFy - Indian Sign Language Detector

## Overview
The Indian Sign Language Detector is a machine learning-based system designed to recognize and classify gestures from the Indian Sign Language (ISL). Utilizing Python's **scikit-learn** library and the **Random Forest** classifier, this project aims to facilitate communication by accurately interpreting ISL gestures.

## Features
- **Random Forest Classifier**: Employs a robust ensemble learning method for accurate gesture classification.
- **Scikit-learn Integration**: Utilizes scikit-learn for efficient model training and evaluation.
- **Custom Dataset**: Incorporates a dataset of ISL gestures for model training and testing.

## Repository Structure
- **data/**: Contains the dataset of ISL gestures used for training and testing.
- **sign-language-detector-python/**: Includes the Python scripts for data processing, model training, and detection.
- **data.pickle**: Serialized dataset object for quick loading.
- **model.p**: Serialized trained model for immediate use.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/varaddeshpande15/Indian-Sign-Language-Detector.git
   cd Indian-Sign-Language-Detector
   ```
2. **Install dependencies**:
   Ensure you have Python installed. Then, install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```
   *Note: If `requirements.txt` is not provided, manually install the required libraries:*
   ```bash
   pip install scikit-learn numpy pandas
   ```

## Usage
1. **Prepare the dataset**:
   - Ensure the `data/` directory contains the labeled ISL gesture images.
   - If starting anew, collect and preprocess ISL gesture images, then place them in the `data/` directory.

2. **Train the model**:
   - Navigate to the `sign-language-detector-python/` directory:
     ```bash
     cd sign-language-detector-python
     ```
   - Run the training script:
     ```bash
     python train.py
     ```
   - This will process the dataset and train the Random Forest model.

3. **Detect gestures**:
   - After training, run the detection script:
     ```bash
     python detect.py
     ```
   - The system will prompt for input gestures and display the classification results.

## Dataset
The `data/` directory should contain subdirectories for each ISL gesture class, with respective images. Ensure that the dataset is well-organized and labeled for optimal model performance.

## Future Improvements
- **Expand Dataset**: Increase the number of gesture samples to improve model accuracy.
- **Real-Time Detection**: Integrate real-time video feed for live gesture recognition.
- **Advanced Models**: Explore deep learning architectures, such as Convolutional Neural Networks (CNNs), for enhanced accuracy.
- **User Interface**: Develop a graphical user interface to make the system more user-friendly.

## Contributing
Contributions are welcome! Please fork the repository, create a new branch for your feature or bug fix, and submit a pull request. Ensure your code follows best practices and is well-documented.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
- **Indian Sign Language Research Community**: For resources and inspiration in developing this detector.
- **Open-Source Contributors**: To the developers of scikit-learn and other libraries utilized in this project.

---
**Author**: Varad Deshpande  
📧 Contact: [varaddeshpande81@gmail.com]  
🔗 LinkedIn: [https://www.linkedin.com/in/varaddeshpande15/]

