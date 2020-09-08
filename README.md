# sym2d_generator
Interactive 2D array positions generator for the 17 symmetry plane groupsi


To create the local python environment and run the notebook locally use the following command:
1. go to the folder where you want to buildd the project:
  cd ~/WHEREEVER
2. download the project from git:
  git clone git@github.com:Arielbs/sym2d_generator.git
3.Build the python environment for the project:
  git clone conda env create -f ~/WHEREEVER/sym2d_generator/util/environmentMin.yml
4. Stage the python environment: (env name is defind in line 1 of environmentMin.yml and can be changed, if change be consistent with the following commands.  
  python -m ipykernel install --user --name con37comp --display-name=con37comp
5. Activate your jupyter notebook (I use screen to be sure not to deactivate my environment axidently):
  a) screen 
  b) juyter notebook
6. Find you notebook, activate and make sure to choose the kernel con37comp

