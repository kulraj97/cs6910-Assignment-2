The wandb report link is: 

**Part A**
1. Question 1
    1. Here we have created a class CNN, in this class we have created a function "create_model" which will return a model based on different parameters which are passed to CNN class. 
    2. Now we have made a model and we will train it on train data and evaluate this model on validation data.
    3. Link for the .ipynb file: https://colab.research.google.com/drive/1iBPfT_DyrMbDc6N4yD8WTQJNRQEQjTlO?usp=sharing
2. Question 2
    1. In this question, we have setup the sweep on the above code.
    2. Here we are adding the parameters like Dropout,Batch Normalization,Doubling,Data Augmentation,Filters in initial layer,Neurons in dense layer,Epochs,Learning rate.
    3. Then we have run the sweep in wandb.
    4. Link for the .ipynb file: https://colab.research.google.com/drive/1z45wclyPdmTCHgJE5VdHyef3eHU1Ye68?usp=sharing
3. Question 4
    1. Here we have run the model on the parameters on which we are getting highest accuracy. We got an accuracy of 35.35% accuracy on the unseen test data.
    2. Then we have taken 30 images from test data and plotted the images with their predicted label in wandb, which is added to the report.
    3. Then we have have plotted the 32 kernal filters of first layer of the best model. We have plotted all the 32 kernels in 4\*8 grid in wandb.
    4. Link for the .ipynb file: https://colab.research.google.com/drive/1_gS_BAjwGMS00cpIDW_il5--bMpelgqr?usp=sharing
    
 4. Question 5
    1. Here we have implemented guided backpropagation on 10 random neurons in the CONV% layer, then plotted the images which excite these 10 neurons.
    2. Since everytime we are picking image randomly and 10 neurons also randomly, so the images we have plotted can aslo vary.
    3. Just by running all the cells you can see the output
    4. We have added the images in 2\*5 grid to the report.
    5. Link for the .pynb file: https://colab.research.google.com/drive/1Y68DiZ98fM23-j1jkBVuPWV4EMWYHnw6?usp=sharing

**Part B**
 1. Question 3
    1. In this question we have setup the sweep using different pretrained model as hyperparameter.
    2. We have added all the losses and accuracies plot in the report.
    3. Link for the .ipynb file:
