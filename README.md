# Fake-News-Detection
The project aims at classifying the given news headlines as fake or true 
Extracted the content of headlines from the given dataset.
Technology used: Python, Pandas, NumPy, scikit-learn

## Prerequisite
What things you need to install the software and how to install them:

1. Python 3.6
    * This setup requires that your machine has python 3.6 installed on it. you can refer to this url https://www.python.org/downloads/ to download python. Once you have python downloaded and installed, you will need to setup PATH variables (if you want to run python program directly, detail instructions are below in how to run software section). To do that check this: https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/.
    * Setting up PATH variable is optional as you can also run program without it and more instruction are given below on this topic.
2. Second and easier option is to download anaconda and use its anaconda prompt to run the commands. To install anaconda check this url https://www.anaconda.com/download/
3. You will also need to download and install below 3 packages after you install either python or anaconda from the steps above
    * Sklearn (scikit-learn)
    * numpy
    * scipy
 
If you have chosen to install python 3.6 then run below commands in command prompt/terminal to install these packages
pip install -U scikit-learn
pip install numpy
pip install scipy

If you have chosen to install anaconda then run below commands in anaconda prompt to install these packages
conda install -c scikit-learn
conda install -c anaconda numpy
conda install -c anaconda scipy

## Process Flow

![Process Flow](https://github.com/Rockyheer/Fake-News-Detection/blob/master/ProcessFlow.png)

##Future steps
* Curating a dataset with more features to improve the accuracy of our model.
* Making the project more userfriendly by deploying it as an efficient GUI.
* Testing out more algorithms.
