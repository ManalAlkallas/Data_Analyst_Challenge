## DS/ML/AI Challenge 
  
    
This is the CodeDoor Coding Challenge for ML/DS/AI.


### Install the Packages

Before you start, install all of the pre-requisite packages. 

*If you don't want to install anaconda on your system, you may want to use `requirements.txt` to install all required packages with pip in your virtual enviroment. Please note that we use Python 3*

If you don't have conda or anaconda installed, you may want to download the Python Anaconda Distribution. Go to [anaconda.org](https://www.anaconda.com/downloads). 


Select the **Python 3.X version** for your OS (it should be automatically chosen). Download and install anaconda.

![select](/docs/select-version.png)

Now that you have conda or anaconda, type the following from **the directory with this code** at the terminal or command prompt.

```bash
conda env create -f environment.yml
```
If you have issues with `environment.yml`, type the following instead.

```bash
conda create -n dsmlai python=3.4 jupyter pandas numpy scikit-learn matplotlib
```

### Activate the Environment with the Packages

Now you need to switch to the environment we just created with the packages installed.  
  
If you are on macOS or linux, run in the terminal

```bash
source activate dsmlai
```

If you are on windows, run at the command prompt

```bash
activate dsmlai
```

Make sure you can run the Jupyter Notebooks

```bash
jupyter notebook
```
In the File Browser, you can navigate to the `notebooks` folder and find the notebook there.  


### What we expect

Commit early and often. You are required to complete each task with at least 1 commit and push your changes. This will let us know where you are and if you need help. **Solutions that contain the whole challenge in one commit will not be accepted!**

For the final submission **Please do not clear your output cells and leave your answer visible.**
