# CIFAR10-Vit-Classification

This project demonstrates a Vision Transformer (ViT) based image classification model implemented in a Jupyter Notebook. The model is trained and evaluated on the CIFAR-10 dataset, which contains 60,000 32×32 color images across 10 different classes. The goal of this project is to perform multiclass image classification using a modern Transformer-based architecture, showcasing how ViT can outperform or complement traditional CNNs for image recognition tasks.

## 📂 Dataset: CIFAR-10
The CIFAR-10 dataset is a widely used benchmark dataset for image classification tasks.
It consists of:

60,000 color images (32×32 pixels).

10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck.

50,000 training images and 10,000 test images.

## 🧩 Data Preprocessing & Augmentation
To improve model generalization and training stability, this project uses data preprocessing and image augmentation techniques with torchvision.transforms.

Key transformations include:

Resize: All images are resized to a uniform target size defined by IMAGE_SIZE.

Random Crop & Padding: Training images are randomly cropped with padding to add slight spatial variance.

Random Horizontal Flip: Randomly flips images horizontally to make the model invariant to left-right orientation.

Color Jitter: Randomly changes brightness, contrast, saturation, and hue to increase dataset diversity.

Normalization: Pixel values are normalized to have mean 0.5 and standard deviation 0.5 to stabilize training.


## 🖼️ Sample Images

### 📚 Training Dataset Examples

![Train Input Image](Image/Training%20input%20image.png)

### 🧪 Test Dataset Examples

![Test Input Image](Image/Test%20input%20image.png)

