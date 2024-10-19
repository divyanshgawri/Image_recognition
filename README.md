**Face Recognition Project**

Overview
This project is a **Face Recognition Project** that employs deep learning techniques to detect and recognize faces in images. The Project utilizes a Convolutional Neural Network (CNN) model trained on a dataset of various individuals. It processes images to identify faces and matches them against known identities, providing confidence scores for each prediction.

## Project Explanation

### Problem Statement

With the increasing use of digital images, the need for effective face recognition systems has grown. This project aims to develop a robust application that can accurately identify individuals from photographs, making it applicable in various fields such as security, personal identification, and social media.

### Key Components

1. **Face Detection**:
   - Uses the `face_recognition` library to locate and crop faces from input images.
   - Handles cases where no faces are detected and returns the original image for further analysis.

2. **Face Recognition**:
   - Utilizes a Self-Made CNN model to classify the cropped face images.
   - Predicts the identity of the individual by comparing the features extracted from the image against those in the training dataset.

3. **Confidence Scoring**:
   - After making a prediction, the application computes the confidence percentage, indicating how likely the prediction is correct.
   - Displays this confidence score alongside the predicted identity, enhancing user understanding of the model's reliability.

4. **Sample Visualization**:
   - Shows the input image and the best-matching image from the dataset, providing a visual representation of the recognition result.

### Technologies Used

- **Python**: The primary programming language for the application.
- **TensorFlow**: For building and training the CNN model.
- **Keras**: Simplifies the process of model creation and training.
- **OpenCV**: For image processing tasks such as resizing and displaying images.
- **Face Recognition**: Library used for face detection and recognition.
- **Matplotlib**: Used for visualizing images and results.
- **NumPy**: Assists with numerical operations and data handling.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/face_recognition_project.git
   cd face_recognition_project
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the trained model (`face_recognition_model.h5`) in the project directory.

## Usage

1. Place your test images in the appropriate directory.
2. Run the main script:
   ```bash
   python main.py
   ```
3. Follow the prompts to input the image path for recognition.

## Example

![Result](https://github.com/divyanshgawri/Image_recognition/blob/main/output.png) 

*Display of original image and predicted class image with confidence percentage.*

## Contributing

If you'd like to contribute to this project, feel free to open an issue or submit a pull request.


## Acknowledgments

- [face_recognition](https://github.com/ageitgey/face_recognition) for face detection capabilities.
- TensorFlow and Keras for deep learning model implementation.

## Contact

For any inquiries or feedback, feel free to reach out to me at [gawridishu@gmail.com].
