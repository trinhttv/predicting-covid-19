# Predicting COVID-19 pneumonia severity from Chest X-Ray images using Convolutional Neural Networks

## Dataset
We used 2 dataset:
- BrixIA COVID-19 Dataset 
[**The data can be downloaded from the website: (https://brixia.github.io/#get-the-data)**]
- COVIDGR1.0 Dataset
[**The data can be downloaded from the website: (https://github.com/ari-dasci/OD-covidgr)**]

## Requirements
- Tensorflow 2.12
- Keras
- Python 3.10.12

## Set up
The experiments of this study were conducted on Google Colab Pro with the following configuration parameters:
- CPU Intel(R) Xeon(R) CPU @ 2.20GHz
- RAM 51GB 
- Memory 166GB
- GPU Tesla V100-SXM2-16GB
- RAM GPU 16GB

## Setting Up Colab Pro Environment
	Step 1:Access the Google Colab Pro homepage: https://colab.research.google.com/.
	Step 2:Log in to your Google account (if not already logged in).
	Step 3:Click on "File" in the menu bar, and then select "New notebook" to create a new notebook.
	Step 4:Once the notebook is created, click on "Runtime" in the menu bar, and then select "Change runtime type".
	Step 5:In the "Change runtime type" window, choose "GPU" under the "Hardware accelerator" section. This will allow you to utilize a GPU for faster model training.
	Step 6:Click the "SAVE" button to save the configuration.
[**These steps will help you set up a Colab Pro environment with GPU acceleration for your machine learning tasks.**]

## Guide to Running Source Code on Google Colab
Part 1: Running files in the model setup section
	Step 1: Access Google Colab
	- Access the main page of Google Colab at: **https://colab.research.google.com/**
	Step 2: Open the Python file in the Setting folder
	- Click on the "File" icon in the top left corner of Colab.
	- Select "Open notebook".
	- Find and select the Python file (corresponding to each model) from the "Setting" folder.
	Step 3: Run the code
	- Click the "Play" button on the left side of each code cell to execute that code.
	- Or press the Shift + Enter key combination to run the code in the current cell.
	Step 4: Save the model after training
## After the code has been executed and the model has been trained, you can save the model by using functions or methods to save the model in your code.
Part 2: Running files in the model evaluation section
	Step 1: Open the Python file in the Evaluating folder
	- Follow the same steps as in Part 1 to open the Python file (corresponding to each model) from the "Evaluating" folder.
	Step 2: Run the code
	- Follow the same steps as in Part 1 to run the code in the corresponding cells.
	Step 3: View the results
	- The results of the code will be displayed right below each code cell.
## Please note that these instructions provide a general guideline for running source code on Google Colab. Be sure to adjust any paths or settings as needed based on your specific project and dataset.
