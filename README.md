# Python Tutorial

1. makes changes
2. Save the file
3. git add .
4. git commit -m "message here"
5. git push


## Creating a Virtual Python Environment

1. Create a virtual environment using the command `conda create -n py_tut python=3.11.7`

2. Activate the virtual environment using the command `conda activate py_tut`

3. Install the following packages using these commands

pip install notebook

pip install ipykernel
python -m ipykernel install --user --name=myenv --display-name="ml_a3"

4. Open the notebook using Jupyter Notebook and choose the kernel ml_a3