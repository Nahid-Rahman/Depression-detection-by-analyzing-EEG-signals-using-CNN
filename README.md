# Depression-detection-by-analyzing-EEG-signals-using-CNN

In this project I tried to detect depression by using CNN which was collected from EDF Data.

The link of the dataset is provided in "Dataset.txt"

#Data Collection Steps:

1- First I collected a EEG brain signal dataset which was in EDF data format

2- I separated the dataset into two types. Major Deppressive Disorder Data and Healthy Data

3- I analyzed each data to generate EEG signal graph and saved them in two folders named "MDD" for Major Deppressive Disorder and "Healthy" for Healthy Data

4- The code for this process is in "Data Read" folder
___________________________________________________________________________________________________

#Detection Process:

1- First I made a basic CNN model both with and without augmentation to see the performance

2- Then using Keras applications built in methods I applied several other built in methods and noted the accuracy of each model

3- Codes of each method are in respective folders under "Keras Application Models"

___________________________________________________________________________________________________

#Custom Model
1- Then finally I made a custom CNN model by myself

2- The model is under "My Custom Model" folder

3- It achieved the highest accuracy among all other models.
