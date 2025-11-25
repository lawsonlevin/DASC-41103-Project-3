# DASC-41103-Project-3

This repository contains the work of two undergraduate Data Science students from the University of Arkansas:
- Alex Castronovo
- Lawson Levin

Download the code file - 'project3.ipynb' along with the '50_images.zip' folder.

When executing the notebook on your machine, ensure the following line contains the correct path to the CNN folder containing the 50 images for training and validation purposes.

In Block 6 (line 2):
- DATA_PATH = "/Users/lawsonlevin/ML/project3/CNN"


Furthermore, in blocks 9 and 10. We have provided code to classify your own images. Ensure the last lines in each of these blocks (the function calls) contain an appropriate path to your image(s).

In Block 9:
predict_single_image(model, r"C:\Users\Alex\Pictures\Screenshots\Screenshot 2025-11-14 153441.png", DEVICE)

In Block 10:
- predict_and_visualize_batch(model, r"C:\Users\Alex\Downloads\ValidationIMG", DEVICE, num_images=5)
