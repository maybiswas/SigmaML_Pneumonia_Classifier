SigmaML Quiz 3 : OpenCV practice with Portrait lady
===================================================

Project Details
---------------

* Training data : ![Kaggle Hackathon Data](https://www.kaggle.com/competitions/123-of-ai-presents-pneumonia-detection-from-xray)
* Github Repository : https://github.com/maybiswas/SigmaML_Pneumonia_Classifier
* Main Notebook : ![pneumonia-classifier.ipynb](https://github.com/maybiswas/SigmaML_Pneumonia_Classifier/blob/main/pneumonia-classifier.ipynb)

* Problem Statement : The goal is to figure out if the patient has pneumonia or not, from X-ray images.
  <img src="https://github.com/maybiswas/SigmaML_Pneumonia_Classifier/blob/main/input/Healthy_Lungs.png" width=50% height=50%>
  <img src="https://github.com/maybiswas/SigmaML_Pneumonia_Classifier/blob/main/input/Pneumonic_Lungs.png" width=50% height=50%>

* Data Distribution of Train set : Healthy VS Pneumonic Lungs
 <img src="https://github.com/maybiswas/SigmaML_Pneumonia_Classifier/blob/main/input/pie-chart.png" width=50% height=50%>

* Output Submission of Test set : https://github.com/maybiswas/SigmaML_Pneumonia_Classifier/blob/main/output/output_submission_eval.csv
* Actuals of Test set : https://github.com/maybiswas/SigmaML_Pneumonia_Classifier/blob/main/output/test_metadata_withindex.xlsx

* Improvements to try :
⋅⋅⋅+ Segment the lung area where cloudy regions / white spots of congestions are present.
+ Try RESNET, VGG16, etc. other CNN pre-trained models for transfer learning.
+ Try Vision Transformer (Vit) or any model that's pretrained on clouds or domain related data.
+ Try more different data augmentation methods like sheer & zoom. Sometimes adding noise / manipulations forces the model to really learn from the augmentations.
+ Try manual class weights if data quality & redundancy is questionable.
+ Use GenAI (like cleanlab).⋅⋅
