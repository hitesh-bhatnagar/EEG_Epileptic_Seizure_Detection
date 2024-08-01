### EEG_Epileptic_Seizure_Detection
## Overview

This project aims to build a Convolutional Neural Network (CNN) for binary classification of EEG signals into seizure and non-seizure classes. 

**EEG_Epileptic_Seizure_Detection.ipynb** contains the code for the model which is trained on dataset from Kaggle.
This notebook contains One Dimension Convolution Neural Network model which has achieved the Test accuracy of 98% .

The project includes data preprocessing, model training, Tuning of Hyperparameters and visualization to provide a comprehensive analysis of the EEG signals.

## Dataset

The dataset used in eeg_project.ipynb is available from Kaggle

Title: Epileptic Seizure Recognition
Authors: Yasir Hussein Shakir 
Year: around 2020
Link: <a href="https://www.kaggle.com/datasets/yasserhessein/epileptic-seizure-recognition">Epileptic Seizure Recognition</a>

## About the Dataset 
----

## Attribute Information:

The original dataset from the reference consists of 5 different folders, each with 100 files, with each file representing a single subject/person. Each file is a recording of brain activity for 23.6 seconds. The corresponding time-series is sampled into 4097 data points. Each data point is the value of the EEG recording at a different point in time. So we have total 500 individuals with each has 4097 data points for 23.5 seconds.

Which is divided and shuffled every 4097 data points into 23 chunks, each chunk contains 178 data points for 1 second, and each data point is the value of the EEG recording at a different point in time. So now we have 23 x 500 = 11500 pieces of information(row), each information contains 178 data points for 1 second(column), the last column represents the label y {1,2,3,4,5}.

The response variable is y in column 179, the Explanatory variables X1, X2, …, X178

y contains the category of the 178-dimensional input vector. Specifically y in {1, 2, 3, 4, 5}:

5 - eyes open, means when they were recording the EEG signal of the brain the patient had their eyes open

4 - eyes closed, means when they were recording the EEG signal the patient had their eyes closed

3 - Yes they identify where the region of the tumor was in the brain and recording the EEG activity from the healthy brain area

2 - They recorder the EEG from the area where the tumor was located

1 - Recording of seizure activity

All subjects falling in classes 2, 3, 4, and 5 are subjects who did not have epileptic seizure. Only subjects in class 1 have epileptic seizure. Although there are 5 classes but our motivation is to do binary classification, namely class 1 (Epileptic seizure) against the rest.

## Project Structure
• Epileptic Seizure Recognition.csv
• eeg_project.ipynb
• EEG_Seizure_detection_model.h5

## Getting started
Make sure to have the following installed :
Python 3.6 or higher 
Jupyter Notebook
Required Python Packages (listed in the 'requiements.txt' file)

## Cloning the Repository


Certainly! Below is a README file tailored for your GitHub repository, including instructions for other users to run your Jupyter notebook, clone the repository, and access the Colab notebook.


To clone the repository, run the following command:
<pre>
git clone https://github.com/your-username/EEG_Epileptic_Seizure_Detection.git
cd EEG-Seizure-Detection
</pre>

## Setting Up the Environment

Create a virtual environment and install the required packages:
<pre>
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
</pre>

## Running the Jupyter Notebook

To run the Jupyter notebook, execute:
<pre>
jupyter notebook
</pre>

Open the eeg_project.ipynb notebook in your browser and run the cells to execute the code.


## Google Colab

Alternatively, you can run the notebook on Google Colab. click the link below to open the notebook directly in Colab environment :

<a href = "https://github.com/hitesh-bhatnagar/EEG_Epileptic_Seizure_Detection/blob/main/eeg_project.ipynb">Colab Notebook</a>

## Visualizations

The project includes various visualizations to understand the EEG signals better:

Heatmaps: Visualizes the EEG signal data as heatmaps.
Spectrograms: Displays the frequency spectrum of the EEG signals.
Time-Series Plots: Plots the raw EEG signal data over time.

## Conclusion

This project demonstrates a comprehensive approach to building a CNN for EEG seizure detection. It includes steps for data loading, preprocessing, model building, training, and visualization. The visualizations, including heatmaps and time-series plots, provide a deeper understanding of the EEG signals and their properties.

## License
This project is licensed under the MIT License 
