# Pot Hole Detection using Transfer Learning and CNN
Using deep learning and transfer learning techniques to solve the binary image classification problem of pothole detection by adopting an accurate model for savings in training time and computational efficiency.

## CNN Transfer Learning
### Convolutional Base
Pre-trained weights from **VGG16**

### Classifiers
  - Fully-connected Layer
  - Global Average Pooling
  - Linear Support Vector Machine

## Installation Requirements
### Environment
We recommend having a **Linux or macOS development environment** for convenience, although the code runs on Windows 10.<br>We recommend using **Anaconda to manage your packages**.<br>Install **Python 3 (version >= 3.8.0 recommended), along with pip**.<br>We also recommend running the code on **Jupyter Notebook**.

### Dependencies
- shutil
- tensorflow
- Keras
- matplotlib
- numpy
- scikit-learn
- joblib

## Instructions
- [ ] Link to the dataset hosted as a drive link
- [ ] Modifications to the code to run on another system (like changes to the basedir variable)
- [ ] Running on jupyter
1. Download or clone this repository locally
2. Run the following commands to install all the dependencies:
```bash
sudo apt update
pip3 install --upgrade pip
pip3 install -r requirements.txt
```
3. Download the dataset from **insert drive link here** into the project directory
4. Launch jupyter notebook from the project directory
5. Open the [source code file](Code/pothole-detection-transfer-learning-CNN.ipynb) titled pothole-detection-transfer-learning-CNN.ipynb
6. Change the basedir variable to the filepath of the dataset folder
7. Restart kernel & run all cells if you want to recompile (NOTE: Tranining takes nearly 4 hrs)
