# IP History Tracking and Company Ranking 
A set of Python scripts to automate the process of tracking Patent assignments for companies and their subsidiaries. With features that identify patent duplication and movement of properties from Assignors to Assignees. A separate script sources general information such as investment and revenue for each company in an arbitrarily long list, to create sortable tables for ranking companies. 

## Installation Instructions 
Follow these steps to install the required software and dependencies to run the Python scripts in this repository. Note: steps can be skipped if certain prerequisites are already installed such as Anaconda. 

### Step 1: Install Python 3
Python can be installed from any number of sources since it is widely used and open-source programming language. For the sake of this repo, a reliable and reputable source is the Anaconda Distribution. For Windows, the Anaconda download can be found here: https://www.anaconda.com/distribution/

Anaconda® is a package manager, an environment manager, a Python/R data science distribution, and a collection of over 1,500+ open source packages. Anaconda is free and easy to install, and it offers free community support.

### Step 2: Download the Python_IP_Ranking Folder (Repository) from GitHub (first time only)
To download the latest release of this code from github, one can simple clone the repository to their local computer. 

2.1  Launch the program called Anaconda Prompt from the Windows start menu. This is a Linux-style terminal interface. 
2.2  Navigate to the folder in which you would like to download the code. Navigation is possible using linux commands such as "cd Desktop/MyCodeFolder". Use "ls" to see a list of the files in the current directory and "pwd" to see the path of your present working directory. 
2.3  Once in your desired folder, enter the follow: "git clone https://github.com/apaulworks/Python_IP_Ranking.git"

### Step 3: Create the Python Environment (first time only)
A Python environment organizes all the dependencies and libraries your code needs in to container from which your scripts can be run. A complete environment is included in the repo you just cloned from GitHub with the name "scrapier.yml".

3.1  Check that you are in the same directory as the cloned repository - you should already be there.
3.2  Install environment by entering the following in the Anaconda Prompt: "conda env create -f scrapier.yml"
3.3  Monitor the installation to see if any fatal errors have occurred. 

### Step 4: Activate the Programming Environment 
Activate the programming environment each time you have restarted your computer or closed out of the Python editor. 

To activate, enter into the Anaconda Prompt: "conda activate scrapier"

If activated successfully, the word "scrapier" should appear in parentheses at the start of each line in the Anaconda Prompt. 

### Step 5: Launch the Editor
The recommended method to run the Python scripts is through the editor and interpreter called Jupyter Notebook. Jupyter Notebook comes preinstalled with the Anaconda Distribution, so no additional installation steps are required here. The Jupyter Notebook interface is simple and runs locally from a browser such as Google Chrome. Make edits, enter comments, push the run button all from one tab. 

To launch Jupyter Notebook, you can either use the Anaconda Navigator which is a gui interface found in your start menu, as would Mircosoft Word. When the Navigator launches, double-click on Jupyter Notebook. A black terminal window will open up (ignore this), followed by a new tab in your browser. 

### Step 6: Run the Code.