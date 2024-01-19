
# CS210_Term_Project 

Berke Ayyıldızlı 31018

# Disclaimer

This readme file only contains the basic information about the project. It just specifies the data, hyphotesis, techniques used and the brief result. For the whole information, please refer to the Term_Project_Report.pdf .

# Overview 

This is the term project for my CS210 - Introduction to Data Science Course. In this project, I wanted to see how my heart rate (beats per minute, BPM) changes according to my driving. To understand the hypothesis and the results better, first, I analyzed the trip data, which I obtained directly from Opel's myOpel app in CSV format. Furthermore, the analysis of my health information, taken from Apple Health, was parsed to only contain BPM, calories, steps taken, and weight data, as the total file was more than 550 MB and consisted of more than 1.7 million lines of code. In the files section, the parsed csv files and term project jupyter notebook can be found. 

For the reasons of security, due to it contains all my device information from 2018 to today, i am not able to upload export.csv file from apple health.

# Project Structure

The project starts with the cleaning part, continues with the basic statistics and the exploratory data analysis part. After the analysis, the findings are then put to the visualisation process, to better understand and comprehend the findings of the datas. After this part, comes the machine learning part, here i used the trip data to train my model to predict my average BPM, with as little error as possible.

# Findings 

As the amount of the data for the trips is lower than the health measurements, although the trend between average speed and average bpm is increasing, it is realtively low to come to a conclusion. The error is caused by both the low numbers of trip data, and the low numbers of measurements of the heart by the apple wathc, as it only measures in a period of time, causing it to miss certain spikes of speed.

# Future Work

To better undestand the correlation and causation between driving skills and the heart health, i should collect more data by putting the apple watch in the activity mode, to cause it to read the BPM constantly, and test it more frequently in different setting while driving. These combined, may lead to a better predictability score in the findings.


# Requirements

Certain libraries and languages are used in this project, to run it, you are needed:

Python 3.x
Jupyter Notebook
pandas
scikit-learn
matplotlib
seaborn

To run the code blocks, you can use the run all button in your ide.


