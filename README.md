# Traffic-Signs-Classifier-Using-Neural-Networks

‣ **OBJECTIVE**

The main objective of our project is to design a model which can automatically classify the road signs so as to assist the user or the machine in taking appropriate actions. Our approach consists of building a model using Convolutional Neural Networks(CNN) by extracting traffic signs from an image using various filters

‣ **ABSTRACT**

In the world of Artificial Intelligence and advancement in technologies, many researchers and big companies like Tesla, Uber, Google, Mercedes-Benz, Toyota, Ford, Audi, etc are working on autonomous vehicles and self-driving cars. One of the many important aspects of a self-driving car is its ability to detect traffic signs in order to provide safety and security for the people not only inside the car but also outside it. So, for achieving accuracy in this technology, the vehicles should be able to interpret traffic signs and make decisions accordingly.
We have focused our project on the German traffic signs. We used the GTSRB traffic sign dataset. The dataset contains about 40,000 images of  different traffic signs. It is further classified into 43 different classes. The dataset is quite varying, some of the classes have many images while some classes have few images.

‣ **DESCRIPTION**

Firstly we have explored the dataset and found that there are a total of 43 classes of traffic signs. The next step in our approach is building a Convolutional Neural Network (CNN) model that will then be used for classifying the given traffic signs.  A  Convolutional Neural Network (CNN)  is a type of neural network model which allows us to extract higher representations for images. Unlike the classical image recognition where we define the image features ourselves, CNN takes the image’s raw pixel data, trains the model, then extracts the features automatically for better classification. 

Our model consists of two main layers, The convolution layer and the pooling layer. Every step in a convolution layer sweeps the window through images then calculates its input and filter dot product pixel values. The use of pooling layer is to reduce the spatial dimension of the input volume for next layers. Note that it only affects weight and height but not depth. The max pool layer is similar to convolution layer, but instead of doing a convolution operation, we select the max values in the receptive fields of the input, saving the indices and then producing a summarized output volume.
Once the desired model is built, we then train the data with our training dataset. After the training was done for a various set of values, we tuned our model to achieve the maximum accuracy of 95.6% on the training data.

Then we tested our model with test dataset and the accuracy we obtained was 95%.
We have also built a GUI in which we have used the saved model (.h5 file) to classify the images that were uploaded into the interface.

‣ **ABOUT THE DATASET**

The German Traffic Sign Recognition Benchmark (GTSRB) contains 43 classes of traffic signs, split into 39,209 training images and 12,630 test images. The images have varying light conditions and rich backgrounds. The dataset is quite varying,  some of the classes have many images while some classes have few images.

Find the dataset here --> https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
