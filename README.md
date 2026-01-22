# Image Color Detection in Google Colab
This Google Colab notebook allows you to detect prominent colors in an image and identify their names. It uses OpenCV for image processing and pandas to manage a dataset of colors.

How to Use
Open the Colab Notebook: Open this .ipynb file in Google Colab.
Upload colors.csv: Ensure you have a colors.csv file available in your Colab environment. If not, upload it to your Colab session (File > Upload). This file contains a list of color names and their RGB values.
Run the Code Cell: Execute the code cell provided in the notebook. This cell will:
Install necessary libraries (pandas, opencv-python).
Prompt you to upload an image file. Select the image you want to analyze (e.g., pic2.jpg).
Process the uploaded image.
Sample colors from predefined points on the image.
Display the image with the detected color names and their RGB values annotated at the bottom.
Requirements
The notebook automatically installs the required libraries:

pandas
opencv-python
Customization
You can modify the sample_points list in the Python code to choose different locations on the image from where colors will be sampled.
You can replace colors.csv with your own CSV file containing color definitions, ensuring it has columns named 'color', 'color_name', 'hex', 'R', 'G', 'B'.
