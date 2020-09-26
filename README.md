# ANT
ANT - Automated NCBI Taxonomy browser is a tool that automates the search for species homosynoyms that have an existing model in AGORA

# SYSTEM REQUIREMENTS
To run the QIIME Pipeline and its supporting python scripts requires:

* A modern Linux operating system.
* Python3 or greater.

# INSTALLATION

ANT is hosted on GitHub

ANT source code and executables can be obtained via two different methods:

Either clone the repository using git:

`git clone https://github.com/Unsaif/ANT`

Or download and extract the zip file using the 'Download ZIP' link of the GitHub project page.

ANT requires the python module selenium. To install execute command:

`pip install selenium`

The program can be run from within the cloned repository or from the location that the zip was extracted to.

This document will assume that ANT is located in your home directory in a folder named `/home/your_username/ANT`. This location will be referred to from hereon in as 'ANTDIR'.
If you have placed ANT in a different location, use that path in place of 'ANTDIR'.

# Downloading geckodriver

Before ANT can be used geckodriver must be downloaded and the extracted executable placed in PATH.

geckodriver can be download here: https://github.com/mozilla/geckodriver/releases

PATH directories can be located by executing command:

`echo $PATH`

# RUNNING THE QIIME PIPELINE

To run the ANT, execute command:

`ANTDIR/ant`

If running from within the pipeline directory:

`./ant`

# OUTPUT

Output is dislayed in the terminal window like so:

`species name: homosynonym`
