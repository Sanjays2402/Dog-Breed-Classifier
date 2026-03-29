# 🐕 Dog Breed Classifier

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

A deep learning pipeline that identifies dog breeds from images. Given a dog photo, the algorithm estimates the breed. Given a human photo, it identifies the most resembling dog breed. Part of the **Udacity Deep Learning Nanodegree** program.

## 📖 About

Build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, the algorithm will identify an estimate of the canine's breed. If supplied an image of a human, the code will identify the resembling dog breed.

Udacity's original repo is [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification).

## 📊 Results

| Model | Test Accuracy |
|-------|:------------:|
| **CNN from Scratch** | 15% |
| **Pre-trained ResNet-50** | **81%** |

## ✨ Features

- 🧠 **Custom CNN** — Built from scratch for baseline comparison
- 🔄 **Transfer Learning** — Pre-trained ResNet-50 for high accuracy
- 👤 **Human Detection** — Uses Haar cascades to detect human faces
- 🐶 **Breed Identification** — Classifies among 133 dog breeds

## 📦 Datasets

- [Dog Dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
- [Human Dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz)

## 🚀 Getting Started

```bash
pip install torch torchvision opencv-python numpy
```

Open `dog_app.ipynb` in Jupyter Notebook.

## 📁 Project Structure

```
├── dog_app.ipynb                          # Main notebook
├── haarcascades/
│   └── haarcascade_frontalface_alt.xml    # Face detection model
└── images/                                # Sample images
```

## 👤 Author

**Sanjay Santhanam**

---

⭐ Star this repo if you found it useful!
