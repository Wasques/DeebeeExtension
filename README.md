# DeebeeExtension
Extension of the tool Deebee, including synthetic data generation and blank filling methods

First of all,
Credits to Marti Miranda for creating the webapp Deebee at first (you can get the original version at https://github.com/martimm00/deebee) he made a really good work keeping the code clean and clear and I keeped it the same way for future use.
Also, credits to David Candela for his study about synthetic data generation and creating the package synthdata (https://pypi.org/project/synthdata/) which is very useful and easy to use once you understand the whole insights of it.

Installation:

  1. Install the packages needed for running the project using the file requirements.txt (some packages were added sicne the last version)
  2. Run the file entrypoint.py
     
         python entrypoint.py

How to use the new functionalities:
  Actually this is pretty easy and the implementation was completely modular, since the new options doesn't affect the original ones and you can use them independently. 
  1. Upload your dataset
  2. Use the options Fill or Generate
