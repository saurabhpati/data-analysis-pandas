# data-analysis-pandas
A small data analysis project using python - language, matplotlib - data visualization lib, pandas - data processing and Jupyter - Ipython
notebook

In order to get going with data analysis on python with pandas, here are the things to get you going, the entire process mentioned below 
should not take more than 15 minutes with a decent internet connection considering you have not done any of these things earlier.

Installing Python (This is the language which we will be using, unless you like R or SAS more):

  1. You can download and install python from https://www.python.org/downloads/ (Choose ~3.6 or higher, this is what has been chosed for 
     this repository.)
  2. Install Python >=3.3 Jupyter notebooks works best with python versions >=3.3 though they have a legacy version going on for python 
     version 2.7.
  
     Jupyter and Ipython work on top of the python framework. So having python is a must.

Installing Jupyter notebooks (This is just the place where we will write our code and see the output):

	1. For me, python was installed at C:\Users\<Username>\AppData\Local\Programs\Python\Python36-32. 
     Navigate to the path where your python is installed and on the address bar type 'cmd' to open the command prompt terminal (Sorry MAC
     users, I have grown to work with Windows as of now, you need to figure out your installation folder and run the terminal from there        
     or navigate to the location, whichever suits you.)
	2. Run the command 'pip3 install jupyter'
	
Installing Pandas (This is the data processing library which provides us with various ways of interpreting the data):

  1. Run the command 'pip3 install pandas' on the terminal in the same location.
  
Installing Matplotlib (Needed to view the data in a visual format like charts, graphs, histograms etc.) :

  1. Run the command 'pip3 install matplotlib'

This should set you up with everyting that is required.

Running the Jupyter Notebook:

	1. Just navigate to any directory where you want to run your notebook.
	2. Over the address bar, open the command prompt and run the command 'jupyter notebook'
	3. A local session will be started on the port 8888 which is the default port for jupyter to run at.
	4. If your port 8888 is busy with some task run jupyter notebook --port 9999 or any other adequate port.
  
Using the notebook:

  1. Create a new notebook by going on the new option on the right and choosing Python 3.
  2. You can rename the notebook by clicking on the existing filename which prompts you to enter the desired filename.

After you are done with your session:
  1. To view the ipynb file for a session, it can be converted to other formats such as pdf or html, the default format is html
	Run the command 'ipython nbconvert filename.ipynb' where 'filename.ipynb' is the name of the file.


