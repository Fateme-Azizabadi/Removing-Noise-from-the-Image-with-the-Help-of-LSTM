# Removing Noise from the Image with the Help of LSTM

**Removing noise from the image with the help of LSTM**

In this project, we deal with image noise reduction with recurrent networks.

## **Gray Scale Image** 

### **Gaussian Noise**

First, we load the image and read it as Gray Scale and add Gaussian noise with variance equal to 100 and zero mean to the image. The original image and the image with noise are shown below.

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Original.Image.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Noisy.Image.png)

Then we select 80% of the pixels as train data and 20% for Validation and Test. We train the network with the following specifications.

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/LSTM.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Result1.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Output1.png)

###  **Salty Pepper Noise**
First, we load the image and read it as Gray Scale and add salty pepper noise with variance equal to 100 and zero mean to the image. The original image and the image with noise are shown below.

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Original.Image.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Salty.Pepper.Noise.png)


Then we select 80% of the pixels as train data and 20% for Validation and Test. We train the network with the following specifications.

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/LSTM2.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Result2.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Output2.png)



## **Color Image**

First, we separate the RGB vectors and add Gaussian noise to each with a variance of 100 and a mean of zero. The original image and the noisy image are shown in the figure below. The vectors R, G, and B are the network's inputs.

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Original.Image.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Salty.Pepper.Noise.png)

Then we consider 80% of the data as Train data and 20% as Validation and Test data. The vectors R, G, and B are the network's inputs. **So the input data is 3D.**

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/Color.LSTM.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/result3.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-the-Image-with-the-Help-of-LSTM/blob/main/Images/output3.png)




 
 
