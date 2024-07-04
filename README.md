### EEG_Epileptic_Seizure_Detection
## Overview

This project aims to build a Convolutional Neural Network (CNN) for binary classification of EEG signals into seizure and non-seizure classes. The dataset used for this project is the CHB-MIT EEG Seizure Analysis Dataset. The project includes data preprocessing, model training, and visualization to provide a comprehensive analysis of the EEG signals.

## Dataset

The dataset used in this project is available from Kaggle

Title: CHB-MIT-Subdataset, EEG Seizure Analysis Dataset
Authors: Badea A., Adam A.
Year: 2021
Link: <a href="https://www.kaggle.com/datasets/adibadea/chbmitseizuredataset">CHB-MIT Seizure Dataset</a>

Reference
Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., … & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.

## Project Structure
• eeg-seizure_train.npz
• eeg-seizure_val_balanced.npz
• eeg-seizure_test.npz
• eeg-predictive_train.npz
• eeg-predictive_val_balanced.npz
• eeg-predictive_val.npz
• eeg-seizure_val.npz
• EEG_Epileptic_Seizure_Detection.ipynb

## Getting started
Make sure to have the following installed :
Python 3.6 or higher 
Jupyter Notebook
Required Python Packages (listed in the 'requiements.txt' file)

## Cloning the Repository


Certainly! Below is a README file tailored for your GitHub repository, including instructions for other users to run your Jupyter notebook, clone the repository, and access the Colab notebook.

EEG Seizure Detection using CNN
Overview
This project aims to build a Convolutional Neural Network (CNN) for binary classification of EEG signals into seizure and non-seizure classes. The dataset used for this project is the CHB-MIT EEG Seizure Analysis Dataset. The project includes data preprocessing, model training, and visualization to provide a comprehensive analysis of the EEG signals.

Dataset
The dataset used in this project is available from Kaggle:

Title: CHB-MIT-Subdataset, EEG Seizure Analysis Dataset
Authors: Badea A., Adam A.
Year: 2021
Link: Kaggle Dataset
Reference:

Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., … & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.

Project Structure
eeg-seizure_train.npz
eeg-seizure_val_balanced.npz
eeg-seizure_test.npz
eeg-predictive_train.npz
eeg-predictive_val_balanced.npz
eeg-predictive_val.npz
eeg-seizure_val.npz
EEG_Seizure_Detection.ipynb (Jupyter Notebook containing the project code)
Getting Started
Prerequisites
Make sure you have the following installed:

Python 3.6 or higher
Jupyter Notebook
Required Python packages (listed in the requirements.txt file)

## Cloning the Repository

To clone the repository, run the following command:
<pre>
git clone https://github.com/your-username/EEG-Seizure-Detection.git
cd EEG-Seizure-Detection
</pre>

##Setting Up the Environment

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

Open the EEG_Epileptic_Seizure_Detection.ipynb notebook in your browser and run the cells to execute the code.


## Google Colab

Alternatively, you can run the notebook on Google Colab. click the link below to open the notebook directly in Colab environment :
<b href = "https://colab.research.google.com/github/hitesh-bhatnagar/EEG_Epileptic_Seizure_Detection/blob/main/EEG_Epileptic_Seizure_Detection.ipynb">Colab Notebook</b>

## Visualizations

The project includes various visualizations to understand the EEG signals better:

Random Image Samples: Displays random EEG signal samples from the training and validation sets.
Heatmaps: Visualizes the EEG signal data as heatmaps.
Spectrograms: Displays the frequency spectrum of the EEG signals.
Time-Series Plots: Plots the raw EEG signal data over time.

## Conclusion

This project demonstrates a comprehensive approach to building a CNN for EEG seizure detection. It includes detailed steps for data loading, preprocessing, model building, training, and visualization. The visualizations, including heatmaps, spectrograms, and time-series plots, provide a deeper understanding of the EEG signals and their properties.

## License
This project is licensed under the MIT License 
