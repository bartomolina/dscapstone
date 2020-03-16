# Flatiron Data Science Bootcamp - Capstone

* Student name: **Barto Molina**
* Student pace: **part time**
* Scheduled project review date/time: **TBD**
* Instructor name: **Victor Geislinger**
* Blog post URL: [TBD](TBD)

## Deliverables

- [Jupyter Notebook](student.ipynb)
- [Presentation](presentation.pdf)
- Blog post: [TBD](TBD)
- [Video walkthrough](TBD)
---

## 1. Introduction
Waste categorization is usually confusing and has some problems: Many times people don't use the correct recycling bins as guidelines for what can and cannot be recycled vary from state to state, even between cities, also, many products have different parts made up of different materials (plastic, glass, paper...). To help classifying the trash into the correct recycling category, we'll build a trash classifier to classify the trash into one of the recycling categories: cardboard, glass, metal, paper, plastic, trash.

The project is going to be based on the [Waster-Sorter](https://towardsdatascience.com/how-to-build-an-image-classifier-for-waste-sorting-6d11d3c9c478) built by Collin Ching, which was inspired by the [trashnet](https://github.com/garythung/trashnet/) classifier by Gary Thung and Mindy Yang.

## 2. The dataset
I'm going to use the same [dataset](https://github.com/garythung/trashnet/#dataset) used in the two projects mentioned before. This dataset contains different 2527 images of products / garbage, organized by material:

- 501 glass
- 594 paper
- 403 cardboard
- 482 plastic
- 410 metal
- 137 trash

## 3. Methodology
The two projects mentioned before use different frameworks and libraries to process the images and build and train the CNN. The original trashnet project uses LUA / Torch, while Collin's project uses the fastai library, built on Pytorch.

For this project, I'm going to replicate Collin's project and build a classifier on TensorFlow / Keras, and compare the similarities and differences between the two.

## 4. Conclusions



## 5. Future work

## 6. References
- [trashnet repo](https://github.com/garythung/trashnet/): The original project and dataset by Gary Thung and Mindy Yang, a CNN network using LUA / Torch.
- [Waste-Sorter](https://towardsdatascience.com/how-to-build-an-image-classifier-for-waste-sorting-6d11d3c9c478) ([repo](https://github.com/collindching/Waste-Sorter)): CNN using fastai (PyTorch) trained with the technet dataset.
- [Dataset in Kaggle](https://www.kaggle.com/asdasdasasdas/garbage-classification): The dataset from the original project in Kaggle. There are different [kernels]((https://www.kaggle.com/asdasdasasdas/garbage-classification) showing different implementations of CNNs.
- [Which Deep Learning Framework is Growing Fastest?](https://towardsdatascience.com/which-deep-learning-framework-is-growing-fastest-3f77f14aa318)
- TensorFlow tutorials:
  - [Load Images](https://www.tensorflow.org/tutorials/load_data/images)
  - [CNN](https://www.tensorflow.org/tutorials/images/cnn)