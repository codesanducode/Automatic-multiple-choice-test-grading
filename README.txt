---------------Packeges---------------
numpy==1.18.1
opencv_python==3.4.2.16
matplotlib==3.1.2
scikit-learn==0.22.1
scipy==1.4.1

--------------File System---------------
Project1/
	should contain template.jpg (provided)
Project1/ground-truth-correct-answers/ 
	should contain all 8 files with the correct answers
lab3/digits
	should contain all the digit images annotated the same as those given in lab3 on moodle
Project1/additional_data/1.scanned/
Project1/additional_data/2.rotated+perspective/
Project1/additional_data/3.no_annotation/
	should contain the images for each task

the source files should be in the same folder as Project1/ and lab3/

------------Running---------------
Running each .ipynb should create the .txt output files in the same folder as the source code

Scenario 1: 
script: scenario1.ipynb
function: grade(image_name) where image_name is the path to the image to be graded
output: gavrila_alexandru_407_task1.txt

Scenario 2:
script: scenario2.ipynb
function: grade(image_name) where image_name is the path to the image to be graded
output: gavrila_alexandru_407_task2.txt

Scenario 3:
script: scenario3.ipynb
function: grade(image_name) where image_name is the path to the image to be graded
output: gavrila_alexandru_407_task3.txt
