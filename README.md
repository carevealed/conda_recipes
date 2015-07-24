# conda_recipes
This contains all the data for installing the Python based script for CAVPP and CAPS

## Setting up Conda for CAVPP/CAPS
1. Make sure you have Conda installed. If you need help installing Conda please check the following links
    * [Mac OS X](http://conda.pydata.org/docs/install/full.html#os-x-anaconda-install)
    * [Windows](http://conda.pydata.org/docs/install/full.html#windows-anaconda-install)
    * [Linux](http://conda.pydata.org/docs/install/full.html#linux-anaconda-install)
    
2. Install the gui launcher (optional, but highly recommended)
Open a terminal and type:
      
   conda install launcher
        
3. Add the following channels to conda:
   
   conda config --add channels http://conda.binstar.org/cavpp/
   conda config --add channels http://conda.binstar.org/henryborchers/

Conda should be now properly installed and configured to run with CAVPP and CAPS scripts

To open the visual launcher, type the following command in the terminal:

   launcher
   
## IMPORTANT
**DO NOT RUN LAUNCHER FROM THE ICON ON THE DESKTOP ON A MAC.**

This make Python run in a different way on OSX which currently prevents the scripts from finding certain dependencies.
