# The Problem
Why should you care about whether your news is real or fake?

* You deserve the truth.  You are smart enough to make up your own mind - as long as you have the real facts in front of you.  You have every right to be insulted when you are presented with fake news, because you are in essence being treated like an idiot.
* Fake news destroys your credibility.  If your arguments are built on bad information, it will be much more difficult for people to believe you now and in the future.
* Fake news can hurt you, and a lot of other people.  Purveyors of fake and misleading medical advice like Mercola.com and NaturalNews.com help perpetuate myths like HIV and AIDS aren't related, or that vaccines cause autism.  These sites are heavily visited and their lies are dangerous.
* Real news can benefit you.  If you want to buy stock in a company, you want to read accurate articles about that company so you can invest wisely.  If you are planning on voting in an election, you want to read as much good information on a candidate so you can vote for the person who best represents your ideas and beliefs.  Fake news will not help you make money or make the world a better place, but real news can.

# Fake-News-Detection
The project aims at detecting the given news as fake or true based on the previously curated dataset where fake and authentic news have already been classified.
Technology used: Python, Pandas, NumPy, scikit-learn, tensorflow.

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

## Future steps
* Curating a dataset with more features to improve the accuracy of our model.
* Completing the model deployment on heroku, making the project more userfriendly.
* Testing out more algorithms.
