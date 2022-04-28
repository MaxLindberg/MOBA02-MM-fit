# MOBA02-MM-fit
A jupyter notebook for fitting the Michaelis-Menten equation to the data from a course lab in "chemistry of the cell" (MOBA02) at Lund university.


## Instructions
1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://docs.anaconda.com/anaconda/install/index.html)
2. Clone this project to your computer (e.g. by downloading as zip and extracting or cloning via git)

3a. (For Linux & MacOS).  Navigate to the local copy (clone) of this repository in a terminal.


3b. (For Windows). Start miniconda/anaconda by pressing start button and type anaconda, select "Anaconda prompt". Navigate to the extracted repository (using `cd`, `cd ..` and `dir`).

4. Create and enter a new conda environment with the required python modules by copying & pasting the following: 
```
conda env create -f environment.yml
conda activate MOBA02
```
5. Start a jupyter lab instance by typing (you could also use the older notebook approach by instead typing `jupyter notebook`): 
```
jupyter lab
```
6. Now you can open the Notebook.ipynb and run through the cells to process and plot my example data
