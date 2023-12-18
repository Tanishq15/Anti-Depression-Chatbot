# Anti-Depression-Chatbot
Anti-depression Chatbot based on principles of Bhagwad Geeta

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites
What things you need to install the software and how to install them:

1. Python 3.6 
   - This setup requires that your machine has python 3.6 installed on it. you can refer to this url https://www.python.org/downloads/ to download python. Once you have python downloaded and installed, you will need to setup PATH variables (if you want to run python program directly, detail instructions are below in *how to run software section*). To do that check this: https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/.  
   - Setting up PATH variable is optional as you can also run program without it and more instruction are given below on this topic. 
2. Second and easier option is to download anaconda and use its anaconda prompt to run the commands. To install anaconda check this url https://www.anaconda.com/download/
3. You will also need to download and install below 3 packages after you install either python or anaconda from the steps above
   - Sklearn (scikit-learn)
   - numpy
   - scipy
   
  - if you have chosen to install python 3.6 then run below commands in command prompt/terminal to install these packages
   ```
   pip install -U scikit-learn
   pip install numpy
   pip install scipy
   ```
   - if you have chosen to install anaconda then run below commands in anaconda prompt to install these packages
   ```
   conda install -c scikit-learn
   conda install -c anaconda numpy
   conda install -c anaconda scipy
   ```
## Final Model Accuracy and Loss
Loss function used in CrossEntropy Loss and the final loss comes out to be around 2.4
and accuracy is about 74 percent.
![IMG-20231217-WA0003](https://github.com/Tanishq15/Anti-Depression-Chatbot/assets/75112914/436524e6-b6b3-4a80-beac-16dd314af6c8)
## Working Chatbot
Final basic GUI of the chatbot looks like this  
![IMG-20231218-WA0003](https://github.com/Tanishq15/Anti-Depression-Chatbot/assets/75112914/42f23d01-419e-40b6-b1cf-a2870a763013)


