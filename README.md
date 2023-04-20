# abhi_rep

Train and Deploy a CNN Model Using TensorFlow Serving
Objective: To build a CNN model using distributed training that can detect diabetic retinopathy and
deploy it using TensorFlow Serving.
Dataset Details:
The dataset contains a large set of high-resolution retina images taken under a variety of imaging
conditions. A left and right field is provided for every subject. Images are labeled with a subject id as
well as either left or right. A clinician has rated the presence of diabetic retinopathy in each image on
a scale of 0 to 4. Like any real-world dataset, you will encounter noise in both the images and labels.
Images may contain artifacts, be out of focus, underexposed, or overexposed.
Steps to be followed:
1. Download and preprocess the dataset to correct for noise and under and over exposure
2. Augment the dataset and split it into training and test sets
3. Define the distributed training strategy
4. Define the number of shared instances
5. Define a CNN architecture to extract features from the model data
6. Define parameters like the loss, optimizer, epochs, learning rate, and evaluation metric
7. Define checkpoints
8. Train the model until an accuracy of at least 80% is obtained
9. Save the model
10. Deploy the saved model using TensorFlow Serving
