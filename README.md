# MoonRocksSemanticSegmentation

- The dataset is taken from [here](https://www.kaggle.com/datasets/romainpessia/artificial-lunar-rocky-landscape-dataset)

- My approach is the following:
- First, try Unet

## Dataset:


"It is often difficult to conduct any kind of machine learning experiment on lunar images because of their scarcity and lack of annotation. The goal of this dataset is to provide the general public with a sample of artificial yet realistic lunar landscapes, which can be used to train rock detection algorithms. Those trained algorithms can then be tested on actual lunar pictures or other pictures of rocky terrain" [Kaggle]

"The dataset currently contains 9,766 realistic renders of rocky lunar landscapes, and their segmented equivalents (the 3 classes are the sky, smaller rocks, and larger rocks). A table of bounding boxes for all larger rocks and processed, cleaned-up ground truth images are also provided. We recommend that users check the "Understanding and Using the Dataset" kernel for additional information and guidelines on how to use the dataset effectively" [Kaggle]

  
## Unet
![img2](https://github.com/SimBoex/MoonRocksSemanticSegmentation/blob/c17bb75d176de7afabc9acb93357da24d82cd776/UnetArchitecture.png)
[source](https://paperswithcode.com/method/u-net#:~:text=U%2DNet%20is%20an%20architecture,architecture%20of%20a%20convolutional%20network)

## VGG16
![img1](https://github.com/SimBoex/MoonRocksSemanticSegmentation/blob/1aadb602db1a1e792c85d0fad1175e07f4f3b8f9/vgg16.png)
[source](https://neurohive.io/en/popular-networks/vgg16/)
