# lp-detect
Demo Web App for detecting license plate characters

### Data Gathering

![image](https://user-images.githubusercontent.com/47663233/129385057-4b3249cd-d8bb-4202-b3fb-0a39a0e95296.png)

This is my personal dataset where the plate images were mostly captured around the college campus/residencies with consent. It also included few scraped images of properly identifiable license plates .The dataset has around 34,000 images of various types of Indian license plates. 

Majority of the number plates are of the [HSRP type](https://parivahan.gov.in/parivahan//en/content/high-security-registration-plates-hsrp-new-vehicle). To expand the size of the dataset, Keras' [ImageDataGenerator](https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator) was used for augmentation(streching, tilting, skewing, etc.).
