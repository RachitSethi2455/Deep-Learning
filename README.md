# Deep Learning Lab Experiments

## Description

This repository contains Deep Learning laboratory experiments implemented using **Python** and **Jupyter Notebook**. The experiments cover fundamental and advanced deep learning concepts, including neural networks, convolutional neural networks, transfer learning, region-based CNNs, image segmentation, autoencoders, and movie genre classification from posters.

## Technologies Used

* Python
* TensorFlow / Keras
* PyTorch / torchvision
* OpenCV, scikit-image
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Experiments Included

1. Introduction to Deep Learning
2. Deep Learning Lab Exercises
3. Cat vs Rabbit Classification
4. Flower Classification
5. Neural Network Lab
6. Multi Layer Perceptron (MLP)
7. Convolutional Neural Network (CNN)
8. Transfer Learning
9. Advanced CNN
10. Region-Based CNN (RCNN)
11. Image Segmentation: U-Net for 6-class land-cover segmentation of aerial images (ISPRS Vaihingen). It reaches 81.5% pixel accuracy and 0.64 mIoU on 17 unseen areas.
12. Advanced Deep Learning
13. Autoencoder
14. Movie Genre Classification from Posters. An improved, standalone version with repeated-split evaluation, Grad-CAM and a demo is at [movie-genre-poster-classification](https://github.com/RachitSethi2455/movie-genre-poster-classification).

## Datasets

| Experiment    | Dataset                                           | Link                                                                                                 |
| ------------- | ------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Experiment 3  | Cat vs Rabbit                                     | https://www.kaggle.com/datasets/muniryadi/cat-vs-rabbit                                              |
| Experiment 4  | Flowers Recognition (5 Classes)                   | https://www.kaggle.com/datasets/alxmamaev/flowers-recognition                                        |
| Experiment 9  | Digit Recognizer (MNIST)                          | https://www.kaggle.com/c/digit-recognizer/data                                                       |
| Experiment 10 | Open Images – Bus & Trucks                        | https://www.kaggle.com/datasets/sixhky/open-images-bus-trucks                                        |
| Experiment 11 | ISPRS Vaihingen (mmsegmentation format): images + annotations | https://www.kaggle.com/datasets/pushkar007/vaihingendataimg, https://www.kaggle.com/datasets/pushkar007/vaihingendataann |
| Experiment 12 | Flower16 (16 Classes)                             | https://www.kaggle.com/datasets/l3llff/flower16                                                      |
| Experiment 14 | IMDb Multimodal Vision & NLP Genre Classification | https://www.kaggle.com/datasets/zulkarnainsaurav/imdb-multimodal-vision-and-nlp-genre-classification |

> **Note:** Experiments that require external datasets use the Kaggle datasets listed above. Download the corresponding dataset before running the respective notebook.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/RachitSethi2455/Deep-Learning.git
   cd Deep-Learning
   ```

2. Install the required dependencies:

   ```bash
   pip install tensorflow torch torchvision numpy pandas matplotlib seaborn scikit-learn scikit-image opencv-python
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open any experiment notebook and run all cells sequentially.

## Author

**Rachit Sethi**
