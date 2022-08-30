```
# install matplotlib
pyenv virtualenvs
poetry config virtualenvs.create false
pyenv virtualenv 3.10.5 data-analysis
pyenv activate data-analysis
export PYENV_VIRTUALENV_DISABLE_PROMPT=1
poetry init
poetry add spacy
poetry add --dev black ipykernel 
python -m ipykernel install --user --name data-analysis
pyenv local data-analysis
poetry add jupyterlab
poetry add matplotlib
poetry add numpy
poetry add pandas
# show version of python installed
pyenv versions
# run jupyter lab
jupyter lab
```

