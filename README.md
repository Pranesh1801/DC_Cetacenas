# DC_Cetacenas
A disease prediction system using Intel One API for Intel One API Hackathon developed by Team Cetaceans. 

Problem Identified: Chronic diseases like Cancer, Diabetes, etc are really dangerous and risk the fact of losing a human's life. Millions of people die every year due to these diseases and this is because these diseases can be cured only if they are identified early. 

Objective: Our project aims to solve this problem or to reduce the risk of losing a human's life by predicting the disease early. An early prediction may ensure for a cure and thus, saving the human's life. This is achieved through Machine Learning integrated with Intel's One API and all these models are connected to a web application.

Solution: To solve this problem, we have developed our Disease prediction system, DC_Cetaceans that is a web application with python codes in the back-end.

![BSP](https://user-images.githubusercontent.com/68537161/235277152-be31d045-28a1-4b19-a584-45c51da1d0d4.png)

# Usage of Intel One API 
Our project has got 3 different Machine Learning models for now and connecting them with Intel One API has increased the efficiency of our model significantly. Intel OneAPI is a software toolkit that enables developers to build and optimize applications for various hardware platforms, including CPUs, GPUs, and FPGAs. OneAPI includes a suite of tools, libraries, and frameworks that can be used to develop Machine Learning applications. One API Data Analytics Library (oneDAL) is a powerful machine learning library that helps you accelerate big data analysis at all stages: preprocessing, transformation, analysis, modeling, validation, and decision making. This library enhances the Random Forest Classifier algorithm and logistic regression algorithm used for the prediction. The library optimizes data ingestion along with algorithmic computation to increase throughput and scalability. It includes C++ and Java* APIs and connectors to popular data sources such as Spark* and Hadoop*. Python* wrappers for oneDAL are part of Intel Distribution for Python.
![b](https://user-images.githubusercontent.com/68537161/235277444-f364da77-bed2-4d88-8ad3-39e10010c3e9.jpeg)

The project mainly uses Random Forest Algorithm because the accuracy and learning rate for that algorithm is comparitively better than other Machine Learning Algorithms. We have used python libraries like scikit learn, matplotlib, pandas, etc and by integrating our project with One API, the performance boosted significantly.
![BBBB](https://user-images.githubusercontent.com/68537161/235277583-13a25f6d-704e-4845-851f-37355d9e5431.png)

# Value for the society

Developing a prediction model through Intel OneAPI to identify individuals who are at risk of developing chronic diseases like Brain stroke or lung cancer or diabetes holds immense value for society. Early intervention in identifying these diseases can bring about significant benefits, such as reducing the likelihood of complications such as heart disease, stroke, kidney disease, blindness, and amputations. Such complications can drastically impact the quality of life of not only individuals but also their families. Moreover, early intervention can also result in cost savings for healthcare systems by reducing the need for costly treatments and hospitalizations. Utilizing Intel OneAPI to create such a disease prediction model allows healthcare professionals to enhance patient outcomes and minimize healthcare expenses, making it an advantageous tool for the betterment of society.

# Scope in the Business industry

Using a prediction model developed with Intel OneAPI to predict chronic diseases like Lung cancer, Diabetes and Brain Stroke can hold significant value for businesses. The healthcare industry, in particular, could benefit from the accurate prediction model as dthese diseases are a major health concern. Healthcare providers can identify high-risk patients with the model's help and offer early intervention and preventive care, resulting in reduced healthcare expenses and better patient outcomes.

Moreover, the insurance industry can leverage the disease prediction model to identify individuals who are more likely to develop cancer or any other disease and adjust their insurance premiums accordingly. This can help insurance companies lower their risks and improve profitability.

![Confusion Matrix](https://user-images.githubusercontent.com/68537161/235278204-44c9a903-59e3-4c0a-bded-1bc528e6d647.png)

# Methodology

So, we have created a web application that initially asks the user about what disease they would like to predict. After this process, the page redirects to the disease asked by the user and some common details are taken. After these details like gender, age, smoking status, work type, etc, the web application sends a request to the respective python file in the back-end. Using the values given as input from the user, the trained Machine Learning model can predict weather a person has the prticular disease or not. 
![LCP](https://user-images.githubusercontent.com/68537161/235278341-afc7efb6-d6d4-4674-858b-ae5699fa8b19.png)

![a](https://user-images.githubusercontent.com/68537161/235277439-f5d3a6f2-b25a-46ca-ab1d-9b618871faca.jpeg)

# Dataset
We have used csv file datasets from Kaggle that have a significant amount of data for an accurate prediction of the disease. Obviously, we have 3 datasets for the 3 different diseases we predict here, that is Lung Cancer< Brain Stroke and Diabetes. Each dataset has about 10-16 columns and above 800 rows of data. 
![DS](https://user-images.githubusercontent.com/68537161/235278701-87a64e77-a53d-44a3-8193-adf979e628b2.png)

# Random Forest Classifier
The Random Forest algorithm is an extensively used and powerful supervised learning method in machine learning. This ensemble learning algorithm constructs multiple decision trees at training time and predicts the class based on the mode of the classes predicted by individual trees. Essentially, the algorithm creates a forest of decision trees and then generates the mode of the classifications made by the individual trees.

The algorithm derives its name from the fact that it randomly selects a subset of features to construct each tree, which reduces variance and improves the model's generalization. The random forest algorithm is highly versatile, capable of being used for classification and regression tasks across various domains, including finance, healthcare, and natural language processing.

One of the most significant benefits of the random forest algorithm is its ability to handle missing data and maintain accuracy even with a large portion of missing data. Moreover, the algorithm is resistant to overfitting, making it an ideal choice for complex datasets with many features. In conclusion, the Random Forest algorithm is a valuable and flexible tool in machine learning with several practical applications.


![ROC](https://user-images.githubusercontent.com/68537161/235278837-70070e96-3a1e-473e-b924-fc61dad7ef90.png)

# Necessary images

![aa](https://user-images.githubusercontent.com/68537161/235279871-6f2774d9-f879-45a7-b70e-bdbfe2de2ee5.png)


![bb](https://user-images.githubusercontent.com/68537161/235279872-67447acb-fa02-4a7d-aba4-f8ff7c0ff399.png)


![Su](https://user-images.githubusercontent.com/68537161/235280832-09a0ac3f-69c0-489a-834f-91137a4ce524.png)


# Conclusion

