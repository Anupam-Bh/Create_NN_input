# Create_NN_input

This matlab based script reads downloaded bandstructure images and creates input for NN model. Two matrices are saved viz. X and Y. The X matrix has the pixel information from the images and acts as input in NN model whereas Y is a vector acting as the target of the NN.

The bandstructure image is divided into 5X5 segments like below:

![image](https://user-images.githubusercontent.com/106304435/170890403-bc09c7b4-4b61-4de3-80d0-3da9ac8c44d8.png)

One has to click on the intended cell and the corresponding cell-id will be stored in the Y matrix as a positive example. 
