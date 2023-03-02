# Color-Line-Cloud---Generative-Art-
Abstract art by dividing an image into tiles, using their average color to create a point cloud, and connecting them with lines. 

![ambilobe-panther-chameleon-breeder-1030x604](https://user-images.githubusercontent.com/88452698/222428050-6c6d0e8c-2eff-4e8a-9c7d-b412aa751259.jpg)

![chamaArtboard 1@4x](https://user-images.githubusercontent.com/88452698/222428170-e6a7bf9a-d5d4-4883-907f-943188d960a6.png)
![chamaArtboard 2@4x](https://user-images.githubusercontent.com/88452698/222428182-f8ef1dda-8ad9-4a05-bd5e-f215c076bf25.png)
![chamaArtboard 2 copy 2@4x](https://user-images.githubusercontent.com/88452698/222428199-6b8456b3-2880-40aa-93bc-4f71b7865b79.png)


This project aims to create a generative art plot using the average color of each tile in an input image. The code takes an image as input and divides it into a specified number of equally sized tiles. For each tile, the average color of all the pixels within the tile is calculated.

Using these average colors, the code generates a set of points, where each point corresponds to the center of a tile. The color of each point is set to the average color of the corresponding tile.

Finally, the code generates a string of lines by connecting each point to its neighboring points in a specified pattern. The color of each line is set to the color of the point of origin. The resulting plot creates a unique abstract image that reflects the color patterns in the original image.

The project uses Python as the main programming language and relies on the following libraries: Pillow for image processing, NumPy for color calculations, and Matplotlib for plotting.

Potential future improvements for this project include exploring different line patterns, such as curved lines, and other parameters to create more varied and personalized generative art plots.
