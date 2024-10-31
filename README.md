# Early-Detection-of-Infertility-in-Women-
Computational Intelligence for Early Detection of Infertility in Women Using Inception and Xception with Attention Mechanism.

Project Overview:-
Computational Intelligence for Early Detection of Infertility in Women Using Inception and Xception with Attention Mechanism.
In this project, I utilized the Fetal Head Ultrasound Images dataset, consisting of 3832 anonymzed images (959*661 pixels) licensed under Creative Commons Attribution 4.0 (CC BY 4.0). This dataset organized into four (04) groups (Trans-Thalamic, Trans-Ventricular, Trans-cerebellum and diverse fetal head images), supports research in medical imaging while maintaining patient confidentiality.

Data Preprocessing:-
The preprocessing steps included loading images, resizing them for uniformity, normalizing pixel values to a range of 0 to 1and applying data Augmentation Techniques like Rotation and Flipping to improve robustness and reduce overfitting.

Model Implementation:-
In here, implemented several Convolutional Neural Network (CNN) architectures for classification
•	Simple CNN: A basic model for image classification
•	Inception: Utilized inception modules for multi-scale feature extraction
•	Inception with Attention: Enhanced feature representation using attention
•	Xception: Leveraged depth wise separable convolutions for efficiency.
•	Xception with Attention: Focused on important features with attention mechanisms.
Each model was evaluated using metrics such as Precision, Recall, F1 Score on a validation dataset.

Result Analysis:-
The performance metrics revealed the following:
•	Simple CNN : Precision = 0.94; Recall = 0.93; F1 Score = 0.93 
•	Inception: Precision = 0.86; Recall = 0.79; F1 Score = 0.79
•	Xception: Precision = 0.85; Recall = 0.82; F1 Score = 0.81
•	Xception with Attention: Precision = 0.84; Recall = 0.74; F1 Score = 0.74
•	Inception with Attention: Precision = 0.45; Recall = 0.36; F1 Score = 0.22
Best Performance in Simple CNN and Poorest Performance in Inception with Attention.
The simple CNN outperformed all models, demonstrating its efficiency in classifying fetal head ultrasound images, while the inception with Attention model faced challenges.

Conclusion:-
This project provided insights into the effectiveness of various CNN architectures for classifying fetal head ultrasound images. The publicly available dataset encourages collaboration and advancements in medical image analysis.
