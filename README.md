# Facial Recognition

A simple facial recognition project using the **Labeled Faces in the Wild (LFW)** dataset. This notebook demonstrates how to load, explore, and visualize facial image data for machine learning tasks.

## Features

- Download the LFW dataset using KaggleHub
- Load face images with Scikit-learn
- Display sample images
- Explore dataset statistics
- Prepare data for facial recognition experiments

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn
- PyTorch
- KaggleHub

## Dataset

This project uses the **Labeled Faces in the Wild (LFW)** dataset, which contains face images of well-known people.

## Installation

Install the required libraries:

```bash
pip install numpy pandas matplotlib opencv-python scikit-learn torch torchvision kagglehub seaborn
```

## How to Run

1. Clone the repository.
2. Open `facial recognition.ipynb` in Jupyter Notebook or Google Colab.
3. Run the notebook cells in order.
4. The dataset will be downloaded automatically.

## Project Structure

```
Facial-Recognition/
│── facial recognition.ipynb
│── README.md
```

## Output

The notebook:
- Downloads the LFW dataset
- Loads face images
- Displays sample faces
- Shows dataset information such as:
  - Number of images
  - Number of people
  - Image dimensions

## Future Improvements

- Train a face recognition model
- Add face detection using OpenCV
- Improve recognition accuracy
- Support real-time webcam recognition
