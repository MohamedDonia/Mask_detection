# Mask detection
in this project, we will train mask detection model based on 12k training pictures from kaggle dateset in this url: https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset
Perform data augmantation of the 10k traing data set to over come over fitting as known that data augmentation is one of the solution of overfitting.
Using Pre-trained model " Mobile net v2" in https://www.tensorflow.org/api_docs/python/tf/keras/applications/mobilenet_v2/MobileNetV2 to tranfer learning to get better accuracy.
getting accuracy for validation set over 99%
![accuracy](https://user-images.githubusercontent.com/81274360/122946189-73aaa980-d379-11eb-9f52-94167dad102c.png)

Testing the model using real images with different faces in the same image 
first we detect faces using haarcascade_frontalface_default and then pass every detected face to our trained model to identify if the person wearing mask or not
![1](https://user-images.githubusercontent.com/81274360/122947430-6f32c080-d37a-11eb-818b-95f316ca5451.png)
![2](https://user-images.githubusercontent.com/81274360/122947439-71951a80-d37a-11eb-971e-cfb0fe09c650.png)
![3](https://user-images.githubusercontent.com/81274360/122947443-72c64780-d37a-11eb-97ee-32d207b7f30a.png)

