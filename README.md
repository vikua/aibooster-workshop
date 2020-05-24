# Time series deep learning workshop

## Prerequisites

- Python 3.7 and pip
- [Jupyter](https://jupyter.org/install) 
- Optional: [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html)
- Optional: [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html)

You need to have Python installed and be able to include the following libraries:
`numpy`, `pandas`, `tensorflow`, `scikit-learn`, `matplotlib`, `IPython`

## Download 

```
git clone git@github.com:vikua/aibooster-workshop.git
```

Or just download as zip 

https://github.com/vikua/aibooster-workshop/archive/master.zip

## Setup

### Choose any installation option

#### Install from requirements file:

```
pip install -r requirements.txt
```

#### For those who prefer to use virtualenv & virtualenvwrapper: 

```
mkvirtualenv tsdlworkshop

pip install -r requirements.txt
```

#### Pure virtualenv:
```
virtualenv tsdlworkshop

source tsdlworkshop/bin/activate

pip install -r requirements.txt
```

### Once installation is complete, you may need to add virtual env as ipython kernel 

```
python -m ipykernel install --user --name tsdlworkshop
```

## Start Jupyter Notebook
1. Open command line terminal
2. Go to `aibooster-workshop` directory
3. At the command line, run `jupyter notebook`
4. Open your web browser to the directed url
5. In the browser, select the "workshop.ipynb" entry


