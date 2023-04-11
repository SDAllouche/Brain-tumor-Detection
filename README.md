# Brain Tumor Detection

In this project, we are going to detect the brain tumor and classify it (either benign or malignant) and then show its position in the image, using deep learning models and transfer learning.

## Convolutive neural networks (CNN) 
CNN are more often used for classification and computer vision tasks. However, they now offer a more evolutionary approach to image classification and object recognition tasks, exploiting the principles of linear algebra, especially matrix multiplication, to identify models in an image.

![image](https://user-images.githubusercontent.com/102489525/231294673-3666944e-20ef-47e1-8bb9-efe0108342f9.png)

## Transfer learning (TL) 
TL is a popular approach in DL where it allows to take advantage of the knowledge (characteristics, weights, etc.) of previously trained models to form new models and even solve problems, such as having less data for the new task.

Also TL is a very beneficial method, it allows to provide fast training progress, you do not have to start from scratch using random initialization weights, but the strongest point is that you can use a small training database to get incredible results.

![image](https://user-images.githubusercontent.com/102489525/231294329-e2fd4f5e-9943-48df-bd49-64ce4fdf1576.png)

## Classification

For classification, we will use the ResNet-50 which is a convolutive neural network of 50 layers of depth. We will load a pre-driven version of the network formed on over a million images from the ImageNet database. The network can classify images into 1000 categories of objects, such as keyboard, mouse, pencil and many animals.

![image](https://user-images.githubusercontent.com/102489525/231294359-add3ce5e-b61d-4ddb-96a8-6e65264bd059.png)

## Segmentation

Res-U-Net, for segmentation, is a CNN that was developed for biomedical image segmentation at the Department of Computer Science at the University of Freiburg, Germany. The network is based on the fully convolutive network and its architecture has been modified and extended to work with fewer training images and to produce more accurate segmentations.
Its operations consist of applying the Convolution on the image for the extraction of characteristics and the Pooling which is used to reduce the dimensions

![image](https://user-images.githubusercontent.com/102489525/231294261-b29bc5fc-d7e6-4352-b99d-8db19f076a37.png)

## License

[MIT License](LICENSE)
