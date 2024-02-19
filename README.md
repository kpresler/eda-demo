# Exploratory Data Analysis Teaching Demonstration 

This repository contains setup instructions, a Jupyter notebook, and an associated dataset for the exploratory data analysis teaching demonstration.


## Setup
1. If you've not got a recent-ish version of Python 3 installed, download it from [here](https://www.python.org/downloads/) and install it before continuing
2. Clone this repository (`git clone https://github.com/kpresler/eda-demo` from Git Bash (Windows) or Terminal (Linux / Mac)) _or_ if you've not got Git installed, click the green `<> Code` button above, then "Download ZIP" & extract the zip file)
3. Install the Python packages we're going to use.  First, to open up an environment we can use for installing packages:
    * Windows with Git installed: right-click in the folder you downloaded the code to, and select Git Bash Here
	
	* Windows without Git installed: launch Command Prompt or PowerShell & `cd` into the directory you downloaded the code to
	
	* Linux/Mac: launch a Terminal & `cd` into the directory you downloaded the code to
	
4. Once you're in a terminal-like environment (Git Bash, Command Prompt, PowerShell, Terminal) run:

    * Windows: `python -m pip install -r requirements.txt`

	* Linux/Mac: `python3 -m pip install -r requirements.txt`
	
This will probably take a couple of minutes depending on the speed of your computer/internet connection


5. Launch the Jupyter server & open it up in your browser:

    * Windows: `python -m notebook`
    
	* Linux/Mac: `python3 -m notebook`
	
This _should_ open Jupyter automatically in your web browser; if not, navigate to `localhost:8888` to access Jupyter.

6. Open up `EDA Demonstration with Activity` (double-click on it from within the Jupyter browser, or single-click and then select Open)

6. You're now ready to follow along with the demonstration!

## Dataset

The dataset we will be analysing comes from the UN, and features some basic demographic data from 1952 to 2007.