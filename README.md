# Deep Learning Model for predicting AIMS-Captcha

Here, we are going to build a deep learning model for predicting AIMS-Captcha. The model is built using Keras and Tensorflow. The model is trained on total 31000 images of AIMS-Captcha with 500 images of each class.

## Data Generation

We can get the data from the from AIMS website by making request to the server. Each image is of 150px with 5 characters in each. Each image is divided into 5 parts and each part is saved as a separate image.

## Data Preprocessing

The data is preprocessed by converting the image into grayscale. The characters in the Captcha are all white. So, we can convert the image into grayscale and then all the pixels that are not white are converted to black. This is done to remove the backgound patterns from the image.

## Training

Now we just need to train the model. We can use any deep learning model for this. I have used a simple CNN model written in tensorflow for this. The model is trained for 10 epochs. The model is saved in the Model folder.