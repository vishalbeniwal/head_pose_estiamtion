Project Description

Head pose estimation has many applications such as driver monitoring, attention recog- nition and multi-view facial analysis. For example, the head pose of a driver can be used to identify if the driver is distracted (e.g. looking at the phone or falling asleep at the wheel). An example commercial system that uses such technology is: FOVIO Driver Monitoring (FDM) processor by Seeing Machines.

In this repository, I have developed a deep convolutional neural network (CNN) to identify the head pose given an image of a person. The head pose is quantified by two values: Tilt - Vertical angle of the head , Pan - Horizontal angle of the head. (The center point of the head in the image, gaze direction etc. are also important parameters for a complete system, but we have ignored that in this project).

The task of the project is to “Predict the head pose of a person given an input image captured from a camera placed directly in front of the person”.

Project-report.pdf: Explains and justify the approaches taken to deal with the problem of developing a deep convolution neural network to identify the head pose of a person given an image.

“modified_data.zip”: Contain all the images (test and train set).

“train_data.csv”: Contain files names of the train set, person id, sequence id for each person, ground truth tilt and pan angles. This data is to be used in developing the models. Use this for your own exploration and evaluation of which approach you think is “best” for this prediction task.

“test_data.csv”: Contain files names of the test set, person id, sequence id for each person. You need to predict the tilt/pan for this data.

“README.txt”: Instructions to run the code

Task1: Run Notebook "dLA1" for head tilt classification

1. Load the notebook into the Jupyter Notebook.
2. Upload the data folder named "modified_data".
3. Create two new empty folder named as "Aug_face90" and Aug_faceNeg90".
4. Uncomment the code under the Data Augmentation Section
5. Run the entire Script

Task2: Run Notebook "dLA1_Pan" for head pan classification

1. Load the notebook into the Jupyter Notebook.
2. Upload the data folder named "modified_data".
3. Run the entire Script
