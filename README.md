﻿# Penguin-Species-Identification

## Summary
The business problem for this project was the failure of the current PENG methodology of penguin identification to keep pace with the amount of raw data that was being collected. Current methodology simply involved a human expert examining raw .csv data and using their expertise and best judgement to identify the species of penguin; this proved to be a tedious and inaccurate method. Proposed was an application that solved this problem by abstracting the process of identification away from the user, relying on machine learning models to predict the species based upon data input by the user. The model application applied algorithms and mathematical models to predict the species at a faster pace than human methodology, with a higher degree of accuracy. By leveraging computing power and mathematics, the application provided an easy-to-use tool for the organization and solved the business problem. A user with access to the application simply must input a few data points for an unidentified species of penguin, and the application automatically predicted the species in real time without any further input from the user. 

## Technology
The application was coded in the Jupyter Notebook using Python. 3rd party machine libraries (Pandas, NumPy, Seaborn, MatPlotLib, Sklearn) were imported directly into the notebook with no installation needed, as Google Colab has built in support for them. The graphical user interface was created by installing and the Ipywidgets library directly into the Colab environment. Various other standard libraries were utilized as well.

## User Guide
### Requirements
The application requires computer with access to the internet.
### Running the Application
1.	Navigate to the application using the provided web link to open up the Notebook in Google Colab: https://colab.research.google.com/github/Dpay123/Penguin-Species-Identification/blob/main/Capstone.ipynb#scrollTo=9b93f4c1

    OR
    
    Create your own Google Colab notebook and choose the "Upload from GitHub" option, using this repository's main URL
2.	After the page loads, wait a few seconds as the Notebook is fully initialized
a.	At the top right you will see the button for settings, sharing, and the Google account icon
b.	The notebook is initialized if it displays “Ram/Disk” information and a check mark
c.	If it displays “Connecting” or “Initializing”, simply wait for a few seconds as the Notebook loads

3.	In the upper left nav, click Runtime > Run all (alternatively, press Ctrl + f9)
a.	This will run all cells of the notebook and execute any code. This process can take up to 30 seconds the first time but is quicker subsequent times
b.	You may encounter a warning, as the live application pulls from the code repository on GitHub – click ‘Run anyway’
 
4.	It will take a few seconds for the application to finish running all the code and generating all the metrics and visualizations, but you will know it is finished when the GUI appears at the bottom of the notebook

Using the Application
1.	Run the application as detailed in the above section
2.	Scroll to the bottom of the notebook where you will find the PENGUIN SPECIES PREDICTION heading and the GUI for the model underneath
3.	Manipulate the data inputs; Island and sex can be selected by dropdown, while body measurements can be selected by clicking and dragging the sliders
a.	The prediction of species is generated automatically when you adjust any of the data inputs, and is seen at the bottom of the GUI

