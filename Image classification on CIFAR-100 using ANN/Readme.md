# **CIFAR-100 Dataset**

**Data Source** - https://www.cs.toronto.edu/~kriz/cifar.html

**Kaggle data card**-  https://www.kaggle.com/datasets/fedesoriano/cifar100/data

The CIFAR-100 dataset (Canadian Institute for Advanced Research, 100 classes) is a subset of the Tiny Images dataset and consists of 60000 32x32 color images. The 100 classes in the CIFAR-100 are grouped into 20 superclasses. There are 600 images per class. Each image comes with a "fine" label (the class to which it belongs) and a "coarse" label (the superclass to which it belongs). There are 500 training images and 100 testing images per class.

### **LOADING DATASET**

We'll be importing the dataset into training and testing halves using Keras library.
Let us understand : label_mode ,an optional parameter in the load_data() to specify label mode. In the CIFAR-100 dataset, there are two label modes: "fine" and "coarse". When label_mode="fine", the dataset will be loaded with the fine-grained class labels, where each image is assigned to one of the 100 specific classes.

