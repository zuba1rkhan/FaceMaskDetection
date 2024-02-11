
# Face Mask Detection Project

## Project Overview
This project aims to develop a machine learning model capable of detecting face masks in images. It focuses on identifying whether individuals are wearing masks, not wearing masks, or wearing masks incorrectly. Given the global need to enhance public health measures, this tool can be instrumental in monitoring adherence to mask-wearing guidelines in various settings.

## Features
- **Data Preprocessing**: Includes grayscale conversion, resizing, and flattening of images, followed by label extraction from XML annotations.
- **Dimensionality Reduction**: Utilizes Principal Component Analysis (PCA) to reduce feature space dimensionality while retaining significant variance.
- **Model Training and Evaluation**: Employs multiple classifiers, including RandomForestClassifier, KNeighborsClassifier, Support Vector Machine (SVM) with various kernels, and LogisticRegression, to identify the most effective model based on precision, recall, and F1-score metrics.

## Getting Started

### Prerequisites
- Python 3.6+
- Libraries: NumPy, OpenCV, scikit-learn, TensorFlow/Keras (for neural network models)

### Installation
Clone the repository to your local machine:
```bash
git clone https://github.com/zuba1rkhan/FaceMaskDetection.git
cd FaceMaskDectection
```

Install the required Python packages:
```bash
pip install -r requirements.txt
```

### Dataset
The dataset consists of images with corresponding XML annotations that label each image as 'with mask', 'without mask', or 'mask weared incorrect'. Images should be placed in a `dataset/images` directory, and annotations in `dataset/annotations`.

## Usage
Run the main script to train the models and evaluate their performance:
```bash
python main.py
```

## Models Evaluated
- RandomForestClassifier
- KNeighborsClassifier
- SVC (with linear, RBF, and polynomial kernels)
- LogisticRegression

## Results
The project includes a detailed analysis of each classifier's performance, emphasizing accuracy, precision, recall, and F1-scores. Based on the evaluation, LogisticRegression was identified as the most effective model, offering a balanced performance across different classes.

## Contributing
Contributions to improve the model or extend its functionality are welcome. Please refer to CONTRIBUTING.md for guidelines.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
- Muhammad Zubair Ahmed Khan - zubairkhan1997@gmail.com
- Emil Alizada - emilalizada0@gmail.com

## Project Links
- [https://github.com/zuba1rkhan/FaceMaskDetection.git](https://github.com/zuba1rkhan/FaceMaskDetection)
- [https://github.com/alizade34/FaceMaskDetection](https://github.com/alizade34/FaceMaskDetection)
