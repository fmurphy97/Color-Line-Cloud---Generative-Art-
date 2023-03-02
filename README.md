# Color-Line-Cloud---Generative-Art-
Abstract art by dividing an image into tiles, using their average color to create a point cloud, and connecting them with lines. 

Source Image
![chameleon sample image](Images/chameleon%20sample%20image.png)

Resulting Image
![result image](Images/result%20image.png)

Some snapshots of the intertwined pattern that results.
![snapshot 1](Images/snapshot%201.png)
![snapshot 2](Images/snaphot%202.png)
![snapshot 3](Images/snaphot%203.png)


## Project Description
This project aims to create a generative art plot using the average color of each tile in an input image. The code takes an image as input and divides it into a specified number of equally sized tiles. For each tile, the average color of all the pixels within the tile is calculated.

Using these average colors, the code generates a set of points, where each point corresponds to the center of a tile. The color of each point is set to the average color of the corresponding tile.

Finally, the code generates a string of lines by connecting each point to its neighboring points in a specified pattern. The color of each line is set to the color of the point of origin. The resulting plot creates a unique abstract image that reflects the color patterns in the original image.

The project uses Python as the main programming language and relies on the following libraries: Pillow for image processing, NumPy for color calculations, and Matplotlib for plotting.

## How to Run
This Jupyter notebook creates an abstract art plot using the average color of each tile in an input image.

### Prerequisites

To run this notebook, you'll need:

- Python 3.x
- Jupyter Notebook
- Pillow
- NumPy
- Matplotlib

### Instructions
Open *"generate_line_art.ipynb"* in Jupyter Notebook.
Set the img_path variable to the path of your input image.
Set the grid_size variable to adjust the total number of points used. The higher the number, the more detailed the resulting plot will be.
Run each cell in the notebook in order.
The final cell will display the generative art plot based on your input image, and will be saved as "result.png".

Note: for a more detailed and lightweight file change the output to svg mode

## Future Improvements
Potential future improvements for this project include exploring different line patterns, such as curved lines, and other parameters to create more varied and personalized generative art plots.
