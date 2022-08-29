# samurAI_project_2
Transfer learning project given at the Global AI hub summer camp'22, by the group samurAI

Drive folder = https://drive.google.com/drive/folders/14I8pBk0j4b45dT0hYLgmmzOPc3EYYsaA?usp=sharing

In this project, we used "Cats and Dogs" dataset from https://www.microsoft.com/en-us/download/details.aspx?id=54765. 
Aim of the project is to train the dataset with a pre-trained model and evaluate the accuracy and loss metrics. 

"Cats and Dogs" dataset is in the "/PetImages" folder. Before preprocessing, we created a new folder named "cat_dog" to collect all the cat and dog images in one folder and renamed them with a format "{class_name}.{index}.jpg", for example, "cat.845.jpg". 

To run the codes successfully, you must add the "ColabNotebooks" folder as a shortcut to your drive.

In samurAI_Project_2_1.ipynb file, we loaded the dataset from drive folder -"/cat_dog"-, preprocessed the data and split the dataset to train, test and validation sets. Then saved as ".npy" file to local and load them to drive (/lists). 
In samurAI_Project_2_2.ipynb file, we trained the data and evaluate the metrics. 
