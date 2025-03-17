# Python Tutorial

1. makes changes
2. Save the file
3. git add .
4. git commit -m "message here"
5. git push


## Creating a Virtual Python Environment

1. Create a virtual environment using the command `conda create -n ml_a3 python=3.11.7`

2. Activate the virtual environment using the command `conda activate ml_a3`

3. Install the following packages using these commands

pip install ipykernel
python -m ipykernel install --user --name=myenv --display-name="ml_a3"
pip install notebook
pip install pandas
pip install matplotlib
pip install scikit-learn
pip install imblearn

4. Open the notebook using Jupyter Notebook and choose the kernel ml_a3