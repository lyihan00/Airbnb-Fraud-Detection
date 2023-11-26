# Airbnb-Fraud-Detection

## General Information
**Data**: _airbnb_fraud.csv_ retrieved from Kaggle (https://www.kaggle.com/datasets/hawkingcr/airbnb-for-boston-with-fraud-detection/data)

**Models**: Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, Neural Network (Keras) and ADABoost

**Tools**: Python, Google Colab

## Business Problem
Airbnb is an accommodations and lodging platform that functions on the basis of trust and security between the platform and its users in the facilitation of the booking transaction. When securing accommodation through Airbnb, guests place their trust in the platform’s security controls to ensure that the listings are authentic and safe. While Airbnb has gained traction as a lodging platform for its diverse geographical options and price ranges, as well as unique localised experiences for guests, it is also attracting the attention of fraudsters who believe the platform serves as a lucrative opportunity for fraud. 

Fraudsters take advantage of the ease of listing accommodation options on the platform and engage in listing fraud. Fraudulent listings include those of non-existent lodgings and those with unauthentic images and promises of amenities provided. While Airbnb has in place verification measures for listings, fraudsters are able to find workarounds to these filtering techniques put in place with evolving technology, such as Googling for real property images at a specific address, or images showing the interior of a property to use as attachments. As such, it remains a challenge for Airbnb to crack down on host listing frauds as fraudsters are evolving together as Airbnb strengthens its ways of detection, finding new ways to bypass the filters Airbnb has in place. 

However, it is important for Airbnb to be able to detect fraudulent listings among all the listings on the platform. From Airbnb’s perspective, the presence of fraudulent listings is costly. Beyond monetary losses, Airbnb suffers social repercussions, where its reputation of being a trustworthy and secure accommodation platform is jeopardised. As such, we recognise that it is vital for Airbnb to include a reliable fraud detection model in their business process, more specifically in their process of screening host listings. 

## Our Aim
Our project aims to find the best-performing model in identifying fraudulent host listings for Airbnb, thereby reducing potential financial and social losses to Airbnb through safeguarding the platform's integrity, fostering positive experiences, and maintaining the reputation of Airbnb as a secure accommodation platform. 

## Dataset
The labelled dataset Airbnb for Boston with fraud detection comprises 21 columns with information on 3586 Airbnb listings in Boston. It includes details such as host response rates, property types, accommodation specifics, pricing, reviews, and more. The last column fraud serves as the target variable (1 = fraud) for our classification task, indicating instances of fraudulent bookings. 

Furthermore, the dataset has a diversity of features, which provides ample opportunities for fine-tuning our ML models by selecting relevant features, adjusting model hyperparameters, and thereby optimising model performance.
