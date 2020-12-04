=====================================================================

This repository contains the material for 

Continental lectures delivered on site at universities. 

The main material is a series of jupyter notebooks.

=====================================================================

ENVIRONMENT:

In order to make the collaboration efficient I have created an environment generator file that contains the essential packages to be used. 
	
	Install:
		Download and install Anaconda:
		https://www.anaconda.com/download/

		Run the following command in Anaconda Prompt (you can find in the start menu) 
		to create the conda environment:

		c> conda create --name ceu_course --file env\conda_env.txt
		c> activate ceu_course
		c> pip install -r env\requirements.txt

	Upgrade environment:

		c> activate ceu_course
		c> conda install --file env\conda_env.txt
		c> pip install -r env\requirements.txt	

	Enable codefolding and table of contents:
	
		c> jupyter contrib nbextension install --user
		c> jupyter nbextensions_configurator enable --user
		c> jupyter nbextension enable codefolding/main
		c> jupyter nbextension enable toc2/main
		
	Use:
		Run the following command in Anaconda Prompt (you can find in the start menu) 
		to start a jupyter notebook:

		activate environment:
		c> activate ceu_course

		start jupyter
		c> jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000000
