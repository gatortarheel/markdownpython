# Elementary Python Data 1

## Objective

Set up a Jupyter environment for future projects.
Jupyter notebooks are good for basic lists, dictionaries and data fundamentals.

## Bookmarks

[CapTech AWS Training](captech-training.signin.aws.amazon.com)  
Teams Wray Mills for access.  
[Serverless API Crash Course](https://cap3totl.com/serverless-api-crash-course.html)  
<!-- <img src="aws-signin1.jpg" style="width: 20%; height: 20%;"> -->

## Setup  

Follow the instructions from [Serverless API Crash Course](https://cap3totl.com/serverless-api-crash-course.html) to get your Cloud9 environment up and running.  
Return to these instructions when Cloud9 is running.  _Stay in your Cloud9 environment in the terminal.  `("name/environment")`_

### To double-check your Cloud9 installation of python ###

* Type `python`
* The command prompt switches to a python environment with your python version listed with details and `>>>`  
* Type `quit()` to exit the python environment  
  
![Alternate text](images/pythonproof.JPG)  

### Install Jupyter ###

* To install Jupyter type `sudo python -m pip install jupyter`  
* To start your instance of Jupyter notebook, type `jupyter notebook --ip=0.0.0.0 --port=8080 --no-browser`
* This will load a Jupyter notebook instance  

 ### Navigate to Jupyter ###  
 To navigate to this notebook, you will need to copy and paste 3 parts of AWS and Jupyter information.  
  
1. Copy/paste this url template into a text editor `https://[ide].vfs.cloud9.[awslocation].amazonaws.com?token=[token]`
2. Copy the part of your Cloud9 instance after the /ide/ and paste it over the `[ide]`  

3. Copy the location of your AWS environment `us-east`, `us-east-2` of your Cloud9 instance and paste it over the `[awslocation]`  

4. From the terminal, copy the token portion of the Jupyter instance.  Paste it over the `[token]`
 ![Alternate text](images/grabthetoken.jpg)  

**Sample Copy Paste Operation**
![Alternate text](images/cloud9jupyter.gif)  

5. Copy and Paste the new URL into a new tab.


This URL should take you to your Jupyter notebook where you should see the cloned repo folder for this assignment.  Open the assignment folder, click on the notebook file (Data 1.ipynb) and you are ready to start the assignment! 


## Git Process

 * GitHub Classroom creates a private repo for your assignment.
 * Clone this repo in your Cloud9 environment with `git clone <repo_name>`.
 <img src="gitcloneelempython.gif"><br/>
 * Do your work on the `dev` branch. Execute `git checkout -b dev` in the Cloud9 console.<br/>
 <img src="gitcheckout1.jpg" style="width: 50%;	height: 50%;">
 * You will be saving your notebook using Jupyter. Jupyter will create many additional autosave files. You only need to commit changes to the main notebook file.
 * Commit and push to your `dev` branch as needed.
 * To _submit_ your assignment, create a PR (Pull Request) [in GitHub?]. This will signal us that your assignment is ready for review.

## Minimum Requirements

* Follow along the Data 1 notebook and add code as appropriate.
* There are 3 sections in the notebook where you should respond with working code or text.
* Your submitted assignment should include a notebook that has been edited with your additional code/solutions.

## Optional Next Steps

* Move the code into a Python program file and create a separate program file tester (using unittest).

## Rubric

| Criteria | Superior (5) | Excellent (4) | OK (3) | Not OK (2) | Unsatisfactory (1) | Grade/Comments |
| --- | --- | --- | --- | --- | --- | --- |
| Readability (50%) | The code is organized (modular) well documented, easy to read and follow. | The code is easy to read and well documented. | The code can be followed. | The code is not easily followed. | The code is a mess. |  |
| Specifications (40%) | The program works and meets all the requirements. | The program works and meets most of the requirements. | The program produces correct results but does not display/plot them correctly. | The program does not meet most of the requirements or fails to display or plot any. | Program does not work at all. |  |
| Efficiency (10%) | The code is highly efficient without affecting readability. | The code is reasonably efficient without affecting readability. | The code runs within a few seconds. | The code runs within a few minutes. | The code takes over an hour to run (or doesn't run at all). | |
