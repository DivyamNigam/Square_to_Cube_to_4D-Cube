# Square_to_Cube_to_4D-Cube
Training a NN to transform square to cube the to 4d cube and understanding 4d shapes better

This project was made to understand 4d shapes. So training a NN to transform a 2d shape to 3d and then to 4d is what you can see below.
Input given should be a tensor of shape (4,2) coordinates of vertices of a square at origin so it should look like this [[0, 0], [a, 0], [a, a], [0, a]] where a can be any natural number.

2D Square

![image](https://github.com/user-attachments/assets/bfefb0ae-3a2f-4b72-882b-d81fff2f9723)


3D Cube

![image](https://github.com/user-attachments/assets/beb45338-3a25-4095-9c97-c303c2358161)


4D Tesseract

![image](https://github.com/user-attachments/assets/f67da372-3b92-4e23-bd18-df996f2b4cc3)


This being done by generating custom dataset and then training 2 nn on it 1st one to display 2d to 3d and 2nd one to represent 3d to 4d.
Plotting of 4d cube is transformed to fit in 3d and is fairly accurate but program does give real 4d coordinates of the tesseract.

Drawbacks: 
Only work for square to cube to tesseract not for other figures but can be trained to transform other shapes.
Input for 2d coordinates are specific because the goal is to see transformation not fit a large amount of data.

