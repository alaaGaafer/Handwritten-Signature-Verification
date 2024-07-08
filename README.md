# Handwritten-Signature-Verification
Handwritten Signature Verification using Siamese Network

This project involves the development of a Siamese Network for verifying handwritten signatures. 
The primary goal is to distinguish between original and forged signatures of students based on provided datasets.


## Dataset

The dataset contains images of handwritten signatures divided into folders for each student. Each student folder contains two subfolders:
- `<student_id>_original`: Contains images of original signatures.
- `<student_id>_forged`: Contains images of forged signatures.

## Project Structure

- `load_data`: Function to load images from the dataset, resize them, and label them accordingly.
- `display_images_with_labels`: Function to display a few sample images along with their labels.
- `generate_dataset`: Function to generate pairs of images (one original and one forged) for training the Siamese Network.
- `SiameseNetwork`: Function to define and compile the Siamese Network model.
- `training and evaluation`: Steps to train the model using the generated dataset and evaluate its performance.

## Dependencies

- Python 3.x
- OpenCV
- TensorFlow
- Keras
- NumPy
- Matplotlib
- scikit-learn
