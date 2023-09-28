## Sprint_15_Project 

# Facial_Analysis

# Project description
The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. You are asked to conduct that evaluation, so as you set to work, keep the following in mind:

 - The shops are equipped with cameras in the checkout area which are triggered when a person is buying alcohol
`- Computer vision methods can be used to determine age of a person from a photo
 - The task then is to build and evaluate a model for verifying people's age
   
To start working on the task, you'll have a set of photographs of people with their ages indicated.

# Project Instructions
1. Perform exploratory data analysis to get an overall impression of the dataset.
2. Train and evaluate the model (it needs to be done on the GPU platform).
3. Combine your code, output and findings (from the previous points) in the final Jupyter notebook.
4. Make conclusions of the model evaluation, add them to the notebook.

# Project Evaluation
1. Have you followed all the steps in the instructions?
2. How did you analyze the data?
3. How did you prepare the data for training/testing?
4. How did you choose parameters for a neural network model?
5. What are your findings and conclusions?
6. Have you kept to the project structure?
7. Have you kept the code neat?

# Generated plot/Image:
<img width="1088" alt="image" src="https://github.com/nhayenquynh/Facial_Analysis/assets/125513684/a4ae3ad4-1f28-4729-ae03-42469ef5a7ab">
<img width="782" alt="image" src="https://github.com/nhayenquynh/Facial_Analysis/assets/125513684/9ebc9271-5729-4809-8daa-8e588a1c9fde">

# Result: 

When created the model with ResNet50 architecture and GlobalAverage2D, Dense layer of 1 with activation 'relu', and learning rate of 0.00005. Then trained the model with 20 epochs, we got a test MAE of 5.79.



