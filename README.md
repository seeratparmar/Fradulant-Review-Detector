# Fradulant-Review-Detection
The project intends to check reviews left by the customers on online platforms for their veracity. It’s purpose is t o separate the untruthful spam from genuine reviews. The project was implemented through an integrated model, with discrete modules being developed and extensively tested individually before their integration.

Pie Chart of Real : Fake review ratio

![image-000](https://user-images.githubusercontent.com/72322378/143286392-d55482b3-734a-4d4f-a7d5-0b2bc132711c.jpg)


Standardization: Pre-processing is applied t o t he input text to standardize the input as per the system’s requirement. The data is tokenized, stopwords removed, lemmatized and finally vectorized to be fed into the CNN model.


CNN Model: The model made use of the ability of the CNN to extract local features of the provided dataset.

Layers of the CNN

![image-004](https://user-images.githubusercontent.com/72322378/143286837-06644c4c-07be-4ac6-954b-4243f8c9015b.jpg)

Activation functions:

<img src="https://user-images.githubusercontent.com/72322378/143286882-aa09c3ec-104b-4425-a383-57dbb3f268f1.jpg" width="400">
<img src="https://user-images.githubusercontent.com/72322378/143286894-1fe9ee38-cc6c-48d3-a576-afea92df3ad9.jpg " width="400">



![image-002](https://user-images.githubusercontent.com/72322378/143286882-aa09c3ec-104b-4425-a383-57dbb3f268f1.jpg )
![image-003](https://user-images.githubusercontent.com/72322378/143286894-1fe9ee38-cc6c-48d3-a576-afea92df3ad9.jpg )




Data Visualisation: The results given by the model are presented in an accessible way to better see and understand trends, outliers, and patterns in data, so that accurate and relevant conclusions can be drawn from them.

![image-005](https://user-images.githubusercontent.com/72322378/143287028-74e0befd-28ff-4801-93c7-59c84e206f8d.jpg)

Accuracy after 7 epochs

![image-006](https://user-images.githubusercontent.com/72322378/143287192-3ba79630-749c-4975-995a-3d0dbab8d5a3.jpg)




Front End: The model is finally deployed on an external platform using cloud. The front end is created and the relevant module plugged into it.

![image-010](https://user-images.githubusercontent.com/72322378/143287316-20caffe2-edda-4de2-8501-c837e0fe9ab5.jpg)



