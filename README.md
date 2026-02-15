This project focuses on the detection of brain tumors from medical images using a YOLOv8-based Convolutional Neural Network (CNN). The objective of the project is to assist in early diagnosis by automatically identifying tumor regions in MRI images with high accuracy. The entire workflow was implemented using Python and executed on Google Colab.

Early detection of brain tumors plays a critical role in effective treatment planning, but manual analysis of medical images can be time-consuming and prone to human error. This project aims to address that challenge by applying deep learning–based object detection techniques to automate the detection process and improve reliability.

The model was built using the YOLOv8 architecture and trained on a dataset of annotated brain MRI images. The dataset was divided using an 80/20 training and validation split.
After training and evaluation, the model achieved a recall score of 0.98 and an F1 score of 0.94, demonstrating strong detection capability and reliability. These results indicate that the model is highly effective at identifying tumor regions while rarely missing positive cases, which is crucial in medical applications.

The project highlights include the implementation of an end-to-end object detection pipeline, effective use of YOLOv8 for medical imaging tasks, and performance optimization focused on real-world applicability. The system shows promise for assisting healthcare professionals by providing fast and accurate preliminary detection.
