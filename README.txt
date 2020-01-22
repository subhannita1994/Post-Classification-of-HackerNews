COMP 6721: Project 2
==========================

This project aims to classify post titles from the social news website [HackerNews](https://news.ycombinator.com/)

# Installation

Download the project repository, unzip it and move it to the development directory


## Python & Required Libraries

Python 3 is required for this project. Check the version of installed Python on your machine by typing the following command (may need to replace `python3` with `python`):
    $ python3 --version  # for Python 3

To install on Windows or MacOSX, download it from [python.org](https://www.python.org/downloads/). If using Python 3.6 on MacOSX, run the following command to install the `certifi` package of certificates because Python 3.6 on MacOSX has no certificates to validate SSL connections.
    $ /Applications/Python\ 3.6/Install\ Certificates.command

On Linux, type:
    $ sudo apt-get update
    $ sudo apt-get install python3 python3-pip


## Using pip 

Note: In order to install pip system wide (i.e. for all users), you must have administrator rights (e.g. use `sudo python3` instead of `python3` on Linux), and you should remove the `--user` option in the following commands.
To make sure the machine has the latest version of pip installed, type in terminal:
    $ python3 -m pip install --user --upgrade pip

To create an isolated environment(optional):
    $ python3 -m pip install --user --upgrade virtualenv
    $ python3 -m virtualenv -p `which python3` env
To activate this environment in Linux/ MacOSX:
    $ source ./env/bin/activate
To activate this environment in Windows:
    $ .\env\Scripts\activate

Use pip to install the required python packages.
    $ python3 -m pip install --upgrade -r requirements.txt


## Starting Jupyter

Type:
    $ jupyter notebook
This should open up the browser with Jupyter's tree view showing the contents of the current directory. If the browser does not open automatically, visit [127.0.0.1:8888](http://127.0.0.1:8888/tree) and click on `index.ipynb`.



