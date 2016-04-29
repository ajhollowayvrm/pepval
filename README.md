# Pepval
A combination of PEP8 Validator and PyDocStringChecker


# Installation
BEFORE INSTALLATION make sure that you have a Python Interpreter and pip installed. 
  1. Download the files to any location.
  2. In the Terminal, navigated to the folder where PepVal is located. 

#Running PepVal
PepVal will do different things based on what it is given as input.
  1. ./pepval.py [options] scriptname.py --> This will run PepVal in the specified file(s). 
  2. ./pepval.py [options] --> This will run ONLY the doc string check on every file in the directory that PepVal is in. 

#Options
  --statistcs -qq  --> How often each error was found.
  --show-source --> Show exactly where the error occurred. 
  --first --> Don't display the same error multiple times. 

