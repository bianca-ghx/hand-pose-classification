# Hand Pose Classification

This project was developed to classify different hand poses using machine learning techniques. The input data consists of hand pose images, and the purpose of this project is to implement a hand pose classification system by extracting features and classifying using kNN, Logistic Regrssion, Random Forest and Support Vector Machine.

## Installation
To install and run this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/bianca-ghx/hand-pose-classification.git
    ```
2. Navigate to the project directory:
    ```sh
    cd hand-pose-classification
    ```
3. Ensure you have Python and the required libraries installed.

## Usage
To use the hand pose classification system, follow these instructions:

1. Prepare your dataset by placing the hand pose images in the appropriate directories as specified in the project.
2. Train the model using the provided training script:
    ```sh
    python train_model.py
    ```
3. Use the trained model to classify hand poses in new images:
    ```sh
    python classify_hand_pose.py --image <path_to_image>
    ```

## Acknowledgements
This project was developed for the Computer Vision 1 laboratory at POLITEHNICA Bucharest National University of Science and Technology to explore hand pose classification in the context of computer vision.
