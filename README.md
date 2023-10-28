# Under-water-image-enhancement
   ![download](https://github.com/bhushanbkt/Under-water-image-enhancement/assets/91175596/c506fb7f-0f81-44a3-9458-8f7ad0784db1)

Under water image enhancement using deep learning 
 underwater object tracking is a difficult task due to the low quality of underwater visual data. Underwater visual data suffers distortions in contrast and sharpness, as a result of refraction and absorption of light, and particles, which all vary dependent on the depth, color and nature of water 



* Data_sets 

1.UIEB Dataset (Underwater Image Enhancement Benchmark):http://irvlab.cs.umn.edu/resources/

2. UIEB-Ref Dataset:http://irvlab.cs.umn.edu/resources/
  
3.UCM underwater dataset: https://www.ux.uis.no/~tranden/

4.SEMEVAL-2021 Task 12 - Underwater Image Enhancement:https://semeval.github.io/semeval2021/
  
5. UOT32 (Underwater Object Tracking) Dataset - https://www.kaggle.com/datasets/landrykezebou/uot32-underwater-object-tracking-dataset/download?datasetVersionNumber=1 (Source - Kaggle)


* Complete EDA for Under water image  - https://www.kaggle.com/code/soumya9977/learning-to-sea-underwater-img-enhancement-eda 
* Under water image enhancement using YOLOv5 (Source - Kaggle)- https://www.kaggle.com/code/awsaf49/great-barrier-reef-yolov5-train


* Steps & task involves -                                                                                                                      1. Data Collection:
Gather a diverse dataset of underwater images with varying visibility and quality. Include both degraded and high-quality images for training and evaluation.
2. Preprocessing: Preprocess the dataset by cleaning and annotating images, removing artifacts, and aligning them for consistency.
3. Model Selection:Choose a deep learning architecture suitable for image enhancement. Convolutional Neural Networks (CNNs) and variants such as U-Net or generative adversarial networks (GANs) are often used for this purpose.
4. Data Augmentation:Augment the dataset with transformations like rotation, flipping, and brightness adjustments to increase model robustness.
5. Model Training:Train the selected deep learning model on the annotated dataset. The model should learn to map degraded underwater images to their enhanced counterparts.
6. Loss Function:Define an appropriate loss function that measures the difference between the predicted enhanced image and the ground truth. Common choices include Mean Squared Error (MSE) or perceptual loss functions.
7. Hyperparameter Tuning:Experiment with different hyperparameters, such as learning rates and batch sizes, to optimize model performance.
8. Evaluation:Assess the model's performance on a separate validation dataset using evaluation metrics like Peak Signal-to-Noise Ratio (PSNR), Structural Similarity Index (SSIM), or perceptual quality metrics.
9. Testing:Test the model on unseen underwater images to evaluate its generalization capability.
