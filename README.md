# AI-Pulmonary_Embolism_Algorithm_DL_Kaggle_Sandbox-Project

This project aims to develop an AI algorithm to detect pulmonary embolisms, showcasing AI’s potential in medical diagnostics. Inspired by my grandfather’s passing from an undiagnosed embolism, this research seeks to contribute to early detection and prevention. By using a sandbox environment like Kaggle, the study highlights AI’s transformative power in improving diagnostic accuracy. The goal is to demonstrate AI’s capability to prevent future losses by enhancing the detection of life-threatening conditions, emphasizing the significant impact these technologies could have on healthcare.

More info at: https://zenodo.org/records/13685334

Model Architecture: 

![image](https://github.com/user-attachments/assets/577716fa-30e0-4cbf-8d42-2871785e5ea5)

-----

Accurate and early detection of diseases through Computed Tomography (CT) imaging is crucial for improving clinical outcomes and reducing diagnostic errors. Currently, manual interpretation of these images by radiologists is prone to errors due to high variability in image quality and heavy workloads. This study addresses the need for automated tools that assist physicians in interpreting CT images, enhancing diagnostic precision and efficiency.

The primary objective of this thesis is to develop an algorithm based on Deep Learning (DL) using an extended DL framework named PyTorch that can analyze CT images and provide accurate diagnoses, thereby demonstrating its feasibility as a clinical support tool. Using an extensive dataset of CT images with more than 6.000 patients (before preprocessing 7,400 patients), I implemented an optimized Convolutional Neural Network (CNN) architecture tailored for the detection of specific pathologies in a sandbox environment such Kaggle.

In this project I developed an architecture model that consisits on two main models, the first one predicts the presence of pulmonary embolisms (PE) and the second model is a multiclassificator that according with the data provided, the algorithm has been trained to predict and detect different features at image level such PE location, PE disease condition and finally hearth ratio.

The results indicate that the binary classification model achieves a 71-74% accuracy in detecting pulmonary embolisms (PE), significantly outperforming traditional methods and aligning closely with existing standards in the state-of-the-art literature. Additionally, at the image level, we achieved notable results: 84-94% accuracy in predicting PE location, 45-65% accuracy in detecting heart ratio, and an accuracy of 4-23% in distinguishing between chronic and acute cases, indicating substantial room for improvement in these specific areas.

In conclusion, the developed algorithm not only meets the precision objectives but also demonstrates its potential to enhance clinical practice in radiological detection. Integrating this technology into hospitals could reduce radiologists’ workload, decrease diagnostic errors, and ultimately save lives by enabling faster and more accurate diagnoses. These findings support the feasibility of implementing DL systems in clinical settings, paving the way for future research and practical applications.

-----

