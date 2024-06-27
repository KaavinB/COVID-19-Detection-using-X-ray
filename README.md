# COVID-19 Detection using Chest X-rays

This project aims to compare the performance of two deep learning models, a custom Convolutional Neural Network (CNN) and a pre-trained VGG-16 model, for the detection of COVID-19 from chest X-ray images.

## Introduction

COVID-19, caused by the novel coronavirus SARS-CoV-2, has become a global pandemic. Early detection and diagnosis are crucial for effective treatment and containment. This project explores the use of deep learning techniques to detect COVID-19 from chest X-ray images.

## Dataset

The dataset used for this project consists of chest X-ray images from patients with COVID-19, as well as healthy controls and patients with other lung diseases. The dataset is preprocessed and augmented to enhance the generalization capabilities of the models.

## Models

### Custom CNN

The custom CNN model is built from scratch using TensorFlow and Keras. It consists of several convolutional, pooling, and fully connected layers designed to extract relevant features from the chest X-ray images and perform classification.

### VGG-16

The VGG-16 model is a pre-trained convolutional neural network originally trained on the ImageNet dataset. In this project, the model is fine-tuned on the chest X-ray dataset to adapt it for COVID-19 detection.

## Installation

To run this project, ensure you have the following dependencies installed:

- Python 3.6+
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib

You can install the dependencies using `pip`:

```bash
pip install tensorflow keras numpy opencv-python matplotlib
```
## Usage

1. Clone the repository:

```bash
git clone https://github.com/KaavinB/COVID-19-Detection-using-X-ray.git
```

2. Run the notebooks:
CNN_Model.ipynb: Contains the implementation and training of the custom CNN model.
VGG-16_Model.ipynb: Contains the implementation and fine-tuning of the VGG-16 model.

3. Follow the instructions in the notebooks to train and evaluate the models.

## Results
The performance of the models is evaluated using various metrics such as accuracy and loss. The results show that the fine-tuned VGG-16 model achieves higher accuracy compared to the custom CNN model, demonstrating its effectiveness for COVID-19 detection.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs, suggestions, or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
