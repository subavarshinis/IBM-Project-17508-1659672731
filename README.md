
# IBM-Project-17508-1659672731
Fertilizers Recommendation System For Disease Prediction

## Fertilizers Recommendation System For Disease Prediction

* Project status: Prototype

## Table of contents

Use for instance <https://github.com/IBM-EPBL/IBM-Project-17508-1659672731>:

>   Fertilizers Recommendation System For Disease Prediction
>   
>       * [Table of contents]
>       
>           * [Problem Statement] - [ https://github.com/IBM-EPBL/IBM-Project-17508-1659672731/blob/main/Problem_Statement_Fertilizer_recomentation_system_for_disease_prediction.pdf ]
>           
>           * [Empathy Map] - [ https://user-images.githubusercontent.com/87495210/189498124-818e4c89-cfda-4961-bd84-85d1c1ab10d2.png ]
>           
>           * [Literature Review] - [ https://github.com/IBM-EPBL/IBM-Project-17508-1659672731/blob/main/IBM_literature%20_survey.pdf ]
>           
## Introduction

Agriculture is the most important sector in today’s life. Most plants are affected by a wide variety of bacterial and fungal diseases. Diseases on plants placed a major constraint on the production and a major threat to food security. Hence, early and accurate identification of plant diseases is essential to ensure high quantity and best quality. In recent years, the number of diseases on plants and the degree of harm caused has increased due to the variation in pathogen varieties, changes in cultivation methods, and inadequate plant protection techniques. 

An automated system is introduced to identify different diseases on plants by checking the symptoms shown on the leaves of the plant. Deep learning techniques are used to identify the diseases and suggest the precautions that can be taken for those diseases. 

## Empathy Map

![badmath](https://user-images.githubusercontent.com/87495210/189498124-818e4c89-cfda-4961-bd84-85d1c1ab10d2.png)

## Literature Review

[1] The proposed method uses SVM to classify tree leaves, identify the disease and suggest the fertilizer. The proposed method is compared with the existing CNN based leaf disease prediction. The proposed SVM technique gives a better result when compared to existing CNN. For the same set of images, F-Measure for CNN is 0.7and 0.8 for SVM, the accuracy of identification of leaf disease of CNN is 0.6 and SVM is 0.8. Advantages : The prediction and diagnosing of leaf diseases are depending on the segmenta-tion such as segmenting the healthy tissues from diseased tissues of leaves. Disadvantages : This further research is implementing the proposed algorithm with the ex-isting public datasets. Also, various segmentation algorithms can be implemented to improve accuracy. The proposed algorithm can be modified further to identify the disease that affects the various plant organs such as stems and fruits. 

[2] Detection of Leaf Diseases and Classification using Digital Image Processing
International Conference on Innovations in Information, Embedded and Communication Systems(ICIIECS), IEEE, 
2017.
Advantages: The system detects the diseases on citrus leaves with 90% accuracy.
Disadvantages:System only able to detect the disease from citrus leaves.
The main objective of this paper is image analysis & classification techniques for detection of leaf diseases and classification. The leaf image is firstly preprocessed and then does the fur-ther work. K-Means Clustering used for image segmentation and then system extract the GLCM features from disease detected images. The disease classification done through the SVM classifier.
Algorithm used: Gray-Level Co-Occurrence Matrix (GLCM) features, SVM, K-Means Clustering .

[3] Semi-automatic leaf disease detection and classification system for soybean culture IET Image Processing, 2018
Advantages:The system helps to compute the disease severity.
Disadvantages:The system uses leaf images taken from an online dataset, so cannot imple-ment in real time.
This paper mainly focuses on the detecting and classifying the leaf disease of soybean plant. Using SVM the proposed system classifies the leaf disease in 3 classes like i.e. downy mildew, frog eye, and septoria leaf blight etc. The proposed system gives maximum average classification accuracyreported is ~90% using a big dataset of 4775 images.
Algorithm used: SVM.

[4] Cloud Based Automated Irrigation And Plant Leaf Disease Detection System Using An Android Application. International Conference on Electronics, Communication and Aero-space Technology, ICECA 2017.
Advantages:It is simple and cost effective system for plant leaf disease detection.
Disadvantages:Any H/w failures may affect the system performance. 
The current paper proposesan android application for irrigation and plant leaf disease detec-tion with cloud and IoT. For monitoring irrigation system they use soil moisture and temper-ature sensor and sensor data send to the cloud. The user can also detect the plant leaf disease. K-means clustering used for feature extraction.
Algorithm used: K-means clustering,
Other than this there are some other levels which can be used for sentimental analysis these are- document level, sentence level, entity and aspect level to study positive and negative, interrogative, sarcastic, good and bad functionality, sentiment without sentiment, conditional sentence and author and reader understanding points.

[5] The author proposes a method which helps us predict crop yield by suggesting the best crops. It also focuses on soil types in order to identify which crop should be planted in the field to increase productivity. In terms of crop yield, soil types are vital. By incorporating the weather details of the previous year into the equation, soil information can be obtained. 
Advantages :It allows us to predict which crops would be appropriate for a given climate. Using the weather and disease related data sets, the crop quality can also be improved. Pre-diction algorithms help us to classify the data based on the disease, and data extracted from the classifier is used to predict soil and crop.
Disadvantages :Due to the changing climatic conditions, accurate results cannot be predicted by this system. 

[6] The current work examines and describes image processing strategies for identifying plant diseases in numerous plant species. BPNN, SVM, K-means clustering, and SGDM are the most common approaches used to identify plant diseases. 
Disadvantages : Some of the issues in these approaches include the impact of background data on the final picture, optimization of the methodology for a specific plant leaf disease, and automation of the technique for continuous automated monitoring of plant leaf diseases in real-world field circumstances.

[7] The proposed method uses SVM to classify tree leaves, identify the disease and suggest the fertilizer. The proposed method is compared with the existing CNN based leaf disease prediction. The proposed SVM technique gives a better result when compared to existing CNN. For the same set of images, F-Measure for CNN is 0.7and 0.8 for SVM, the accuracy of identification of leaf disease of CNN is 0.6 and SVM is 0.8. Advantages : The prediction and diagnosing of leaf diseases are depending on the segmenta-tion such as segmenting the healthy tissues from diseased tissues of leaves. Disadvantages : This further research is implementing the proposed algorithm with the ex-isting public datasets. Also, various segmentation algorithms can be implemented to improve accuracy. The proposed algorithm can be modified further to identify the disease that affects the various plant organs such as stems and fruits.  
[8] In this paper, we propose a user-friendly web applicationsystem based on machine learning and web-scraping calledthe ‘Farmer’s Assistant’. With our system, we are successfully able to provide several features - crop recommendation using Random Forest algorithm, fertilizer recommendation using arule based classification system, and crop disease detection
using EfficientNet model on leaf images. The user can provide the input using forms on our user interface and quickly gettheir results. In addition, we also use the LIME interpretability method to explain our predictions on the disease detectionimage, which can potentially help understand why our modelpredicts what it predicts, and improve the datasets and models us-ing this information.
Advantages : For crop recommendation and fertilizer recommendation, we can
provide the availability of the same on the popular shopping websites, and possibly allow us-ers to buy the crops and fertilizers directly from our application.
Disadvantages : To provide fine-grained segmentations of the diseased portion of the dataset. this is not possible due to lack of such data. However, in our application,we can integrate a segmentation annotation tool where theusers might be able to help us with the lack. Also, we can usesome unsupervised algorithms to pin-point the diseased areas
in the image. We intend to add these features and fix thesegaps in our upcoming work. 

## References:

[1] Semi-automatic leaf disease detection and classification system for soybean culture IET Image Processing, 2018

[2] Cloud Based Automated Irrigation And Plant Leaf Disease Detection System Using An Android Application. International Conference on Electronics, Communication and Aerospace Technology, ICECA 2017.

[3] Ms. Kiran R. Gavhale, Ujwalla Gawande, Plant Leaves Disease detection using Image 
Processing Techniques, January 2014.
https://www.researchgate.net/profile/UjwallaGawande/publication/314436486_An_Overview_of_the_Research_on_Plant_Leaves_Disease_detection_using_Image_Processing_Techniques/links/5d3710664585153e591a3d20/An-Overview-of-the-Research-on-Plant-Leaves-Diseae detection-using-Image-Processing￾Techniques.pdf

[4] Duan Yan-e, Design of Intelligent Agriculture Management Information System Based on 
IOTǁ, IEEE,4th, Fourth International reference on Intelligent Computation Technology and Automation, 2011
https://ieeexplore.ieee.org/document/5750779 

[5] R. Neela, P. Fertilizers Recommendation System For Disease Prediction In Tree Leave International journal of scientific & technology research volume 8, issue 11, november 2019
http://www.ijstr.org/final-print/nov2019/Fertilizers-Recommendation-System-For-Disease-Prediction-In-Tree-Leave.pdf .

[6] Swapnil Jori1, Rutuja Bhalshankar2, Dipali Dhamale3, Sulochana Sonkamble , Healthy Farm: Leaf Disease Estimation and Fertilizer Recommendation System using Machine Learning,International Journal of All Research Education and Scientific Methods (IJARESM), ISSN: 2455-6211

[7] Detection of Leaf Diseases and Classification using Digital Image Processing
International Conference on Innovations in Information, Embedded and Communication Sys-tems(ICIIECS), IEEE, 
2017.

[8] Shloka Gupta ,Nishit Jain ,Akshay Chopade, Farmer’s Assistant: A Machine Learning BasedApplication for Agricultural Solutions.


## References: 

![image](https://user-images.githubusercontent.com/89697515/189512983-8f4757ef-6f88-4a87-b3c3-9755d09a61e5.png)

