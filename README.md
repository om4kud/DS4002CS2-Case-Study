# DS4002CS2-Case-Study
Handwriting Detection Analysis
# DS 4002 Project 2

## Table of Contents

[DATA](#Data)  - This section contains sections of the IAM dataset which the model is trained on. The dataset consists of images of handwritten words. The entire dataset can be accessed from https://fki.tic.heia-fr.ch/databases/iam-handwriting-database.

[References](#References)  - This section contains all references that were used throughout the project, as well as links to the MI1 and MI2 Assignments.

## SRC

### Installing/Building Code
To install/build the code, VSCode and Python is required. Then, the scripts in the 'src', 'model', and 'data' folder are required to run the code. To run and test the model on an example image, cd into the 'src' directory and run 'python main.py --img_file ../data/line.png' in the terminal. 

Required libraries:
- cv2
- editdistance
- path
- tensorflow


### Usage of Code
The code can be used to replicate our deep-learning model or build upon it.

## DATASET

### Link to Dataset
[See file](https://fki.tic.heia-fr.ch/databases/iam-handwriting-database)

### Data Dictionary
| Column| Description|                   
|-------|------------|
| graylevel | graylevel to binarize the line containing the word in the dataset|
| bounding box | the bounding box around the word in x,y,w,h format | 
| grammatical tag | the grammatical tag for the word (noun, verb, adjective) | 
| transcription | the transcription for words in the dataset | 


## REFERENCES 

[1] "IAM Handwriting Database," fki, [Online]. Available: https://fki.tic.heia-fr.ch/databases/iam-handwriting-database. [Accessed: 08-Oct-2023]. 

[2] “Handwriting Recognition Guide,” v7labs, [Online]. Available: https://www.v7labs.com/blog/handwriting-recognition-guide#:~:text=Improved%20accessibility,blind%20and%20visually%20impaired%20individuals. [Accessed: 08-Oct-2023]. 

[3] "Train your image classifier model with PyTorch," Microsoft, [Online]. Available: https://learn.microsoft.com/en-us/windows/ai/windows-ml/tutorials/pytorch-train-model. [Accessed: 08-Oct-2023]. 

[4] “Mahotas: Computer Vision in Python,”mahotas.readthedocs.io, [Online]. Available:
https://mahotas.readthedocs.io/en/latest/features.html.
[Accessed: 15-Oct-2023]

[5] "Unpacking the State-of-the-Art in Handwritten Text Recognition", [Online]. Available: https://slator.com/unpacking-state-of-the-art-handwritten-text-recognition/ [Accessed: 6-Dec-2023]

