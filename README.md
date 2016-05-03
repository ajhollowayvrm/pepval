# Pepval
A combination of PEP8 Validator and PyDocStringChecker


# Installation
BEFORE INSTALLATION make sure that you have a Python Interpreter and pip installed. 

Without pip
  1. Download the files and extract to any location. 
  2. In a command line window, navigate to the PepVal-master folder that was created.
  3. Run ./pepval and the necesarry dependencies will be installed. 

With pip
  1. Simply type "sudo pip install pepval" in a command line window. 
  2. Once again, you must be in the folder to user PepVal. The default installation folder when using pip install is /usr/local/bin/    
  

#Running PepVal
PepVal will do different things based on what it is given as input. *These commands must be run while inside the folder where PepVal is contained. However, the path to the files or directory being validated can be anywhere.*
  1. ./pepval [options] scriptname.py --> This will run PepVal in the specified file(s). 
  2. ./pepval [options] ../directoryname --> This will run PepVal on every file in the selected directory. *NOTE: There is a weird bug with PyDocStyle where an error occasionally occurs dealing with bad functions.*


#Options
  1. --statistcs -qq  --> How often each error was found.
  2. --show-source --> Show exactly where the error occurred. 
  3. --first --> Don't display the same error multiple times. 

