Image Manipulator

Goal of the Image Manipulator program:
- With this project you can perform different image manipulations, using Python program.

The program consists of two notebooks which are located in directory notebooks/:
1/ image_manipulations.ipynb: manipulations of image: multiplying images in a grid, flipping and colouring images in a grid around a central larger image. These are one-offs, without generalisation functions. 
2/ image_manipulation_functions.ipynb: Generalising functions of image manipulations: image multiplication, grid with flips, colourful grid around a central larger image, grid with degrading colours, image blurrer. For ease of use, the different functions are added into one notebook

Each notebook starts with the loading of an image.
Each function can be applied to different images, and with different counts of rows and columns. 

Necessary data:
- an image is needed in order to run the Jupyter Notebooks, an example is available: /data/input/image_raw.png
- other images could be used if named as 'image_raw.png' or if naming is changed in code 
- no other data than an image is needed

Necessary Python packages:
See image_manipulator.yml for a full list of environment, amongst others:
- numpy Version 1.26.3
- numpy-base Version 1.26.3
- notebook (Jupyter Notebook) Version 6.5.4
- matplotlib Version 3.8.0
- os Version
- PIL

Github repository contains all necessary info:
- https://github.com/cdieltje/numpyimagemanipulator




