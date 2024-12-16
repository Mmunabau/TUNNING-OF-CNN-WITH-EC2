<h1>TUNNING OF CNN WITH EC2</h1>

<h2>Description</h2>
This project aims to build, train, and optimize a Convolutional Neural Network (CNN) for image classification tasks using AWS EC2. The goal is to leverage AWS cloud infrastructure to handle computationally intensive tasks, ensuring scalability, efficiency, and cost optimization.

The project involves creating a robust pipeline to preprocess image data, build a CNN architecture, and tune hyperparameters to achieve high classification accuracy. By deploying the model on GPU-enabled EC2 instances, the training process will be accelerated, making it suitable for handling large datasets.

Additionally, the project will explore performance optimization techniques such as learning rate scheduling, regularization, and efficient resource utilization on EC2. The trained model will be evaluated on test data to ensure generalization and accuracy, and the results will be visualized for insights..

<h2>Objectives:</h2>
- <b>Set up an EC2 instance with appropriate machine learning frameworks (e.g., TensorFlow, PyTorch).</b><br>
- <b>Preprocess a large dataset of images for CNN training and evaluation.</b><br>
- <b>Design and implement a CNN architecture tailored to the dataset.</b><br>
- <b>Train the model on EC2 using GPU acceleration for faster computation.</b><br>
- <b>Optimize the model using hyperparameter tuning techniques.</b><br>
- <b>Evaluate model performance and visualize results.</b><br>
- <b>Explore cost-efficient strategies for cloud computing resources.</b>
<br />


<h2>Expected Outcome:</h2>

- <b>A trained CNN model with high accuracy for image classification.</b> 
- <b>Detailed insights into the impact of hyperparameter tuning and cloud optimization on model performance.</b>
- <b>Documentation of cost-efficient resource utilization on AWS EC2.</b>
  
<h2>Tech stack:</h2>

- <b>AWS CONSOLE.</b> 
- <b>AWS EC2: For scalable compute resources.</b>
- <b>TensorFlow/Keras or PyTorch: For building and training the CNN.</b>
- <b>JupyterNotebook(Python): For coding and model implementation.</b>

<h2>Program walk-through:</h2>

<p align="center">
Creat a sagemaker Domain launch tap the sagemaker canvas: <br/>
 <img src="image/sg-1.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />
 
<br />
Navigate to your s3 bucket upload your Dataset in csv format:  <br/>
<img src="image/sg-2.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />

<br />
Creat Model <br/>
<img src="image/sg-3.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />

<br />
Import your dataset into the model from the source(s3):  <br/>
<img src="image/sg-4.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />
select the column you trying to predict:  <br/>
<img src="image/sg-5.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />
selcet the Quick build:  <br/>
<img src="image/sg-6.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />
the below image is your model status/click predict:  <br/>
<img src="image/sg-7.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />
import your predict dataset from (s3):  <br/>
<img src="image/sg-9.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
<br />
Download your predicted dataset:  <br/>
<img src="image/sg-10.jpg" height="80%" width="80%" alt="TF-IDF Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
