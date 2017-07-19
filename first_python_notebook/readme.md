# First Python Notebook

```bash
git clone first_python_notebook@...
cd first_python_notebook
conda env create -f environment.yml
jupyter notebook &

# First time setup:
mkdir first_python_notebook
cd first_python_notebook
conda create --name first_python_notebook python
source activate first_python_notebook
which python
pip install jupyter
pip install matplotlib
pip install pandas
git init .
git status
git add *.ipynb
conda env export > environment.yml
#pip freeze > requirements.txt
```
