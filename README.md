# Future-Ready-Talent-
This is my Final Project Demonstration for Future ready Program 2k22 This project deal with Fake news Detection 
# Fake-News-Detection Chrome Extension that uses TFid ML to identify fake news.

# Conditions
1. A browser based on Chromium (i.e Google Chrome, Microsoft edge chromium based browser)
2. Internet access

# Installation 
1. Select Extension from the Chrome menu under More Tools.

2. Activate "Developer Mode" and select "Load Unpacked."

3. Click on select folder after navigating to the "Chrome Extension" Folder.

Your installation of the Chrome extension was successful.


The chrome extension's backend is called "Azure Function." Go to the "Azure Function" folder to learn more about the backend.

The dataset and ML model under the "Machine Learning Model" folder will predict if the news is true or false.
For more details, go to the "Machine Learning Model" folder.

Information ##
This section is utilised to develop an ML model.

Dataset for training
There is a training dataset in the file "news.csv."

How do I make a model?
Execute the cells in the notebook "Fake News Detection.ipynb" in Jupyter Notebook.

# Results
You will thus receive the "final model.sav" file, which contains our finished trained model.
Additionally, Azure Function makes advantage of this concept.

# How it works
The ML model which is created in "Machine Learning Model" which is `final_model.sav` is imported here.
This model is connected using Azure Function and deployed on Azure using 'Visual Studio Code'.

This provides backend to our chrome extension.

# How to deploy 
Open this folder in Visual Studio and then please refer to this article https://docs.microsoft.com/en-us/azure/azure-functions/functions-develop-vs
# API
After deployment, 'Visual Studio Code' will give you a HTTP API which you can use in `Chrome extension/popup.js`
