I have implemented Image-Caption generator. In this project, At first pretrained VGG-16 model was used for extracting the features of the images. Then preprocess the captions to remove the unneccessary characters and white spaces. Then a keras model using LSTM is trained using the fliker8K dataset. The BLUE score for 1 gram precision is 0.5328.
The architecture of model is shown below:
 ![image](https://github.com/sanjoggaihre/Image-Caption-Generator/assets/43695490/9d78ed0d-c012-481e-aefb-3ed3b31efa4a)
