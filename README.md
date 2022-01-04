# Deep Learning Classifier of Lung Illnesses

Created By Dillon Medd

# Project Introduction:
This project was completed using the [Kaggle Covid-19 Image Dataset](https://www.kaggle.com/pranavraikokte/covid19-image-dataset). This contained a collection of 317 X-ray lung scans from patients that either had Covid-19, pneumonia or a healthy set of lungs. An example of each is shown below.

![image](https://user-images.githubusercontent.com/79603572/148129908-c50780e5-2762-4293-9bc7-8f430587d87f.png)

The main goal of this project will be to create a deep learning model, using the tensorflow and keras libraries, that will accurately classify an image into one of the three cateogries (Covid, Normal, Pneumonia)

# Model Training and Evaluation

The model used to make these predictions was a sequential model containing an input layer, two hidden convolutional layers, an output layer using softmax activation and compiled with the adam optimizer. The model summary is displayed below.

![image](https://user-images.githubusercontent.com/79603572/148131437-53b81932-9a15-4d12-85b0-5e8be76f97ae.png)

Below you can find the training and validation accuracy of our model at up to 40 epochs, the leveling out of validation accuracy lead to the final model using just 20 epochs in the training process

![image](https://user-images.githubusercontent.com/79603572/148131819-85a9b2f8-26be-4fba-b02d-0969b0ef743f.png)

Overall I was extremely satisfied with the models ability to classify lungs into the correct category, there was an overall accuracy of 89%, and a covid-19 recall of 96%. Below is a confusion matrix comparing the model's predictions and the dataset's correct values.

![image](https://user-images.githubusercontent.com/79603572/148132076-c0426746-85ad-4f34-a418-5068ee6b08d2.png)

# Thank you!
For more information on this project, check out the [working notebook](https://github.com/dmedd98/covid_classification/blob/main/working_nb.ipynb)
Check out my github and LinkedIn to see more projects like this!
  - [Github](https://github.com/dmedd98)
  - [LinkedIn](https://www.linkedin.com/in/dillon-medd/)
     
