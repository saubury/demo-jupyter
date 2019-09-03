# Prerequisites

## Python and Pip
- `python3 --version` - should be Python 3.7 or later
- `pip3 --version` - should be pip 19 or later

## Clone this code
```
mkdir git
cd git
git clone https://github.com/saubury/demo-jupyter
cd demo-jupyter
```

## Setup
```
pip install virtualenv
virtualenv myjupyter
source myjupyter/bin/activate
pip install -r requirements.txt
jupyter notebook
```

## Fixes
If you see _“jupyter: command not found”_
```
pip3 install jupyter
```

If you see _Cannot assign requested address_
```
jupyter notebook --ip=0.0.0.0 --port=8080
```

# Supporting Libraries
| Library | Description
| - |- |
| ipykernel | Iteractive Python shell and a Jupyter kernel 
| numpy | Efficient multi-dimensional container of generic data
| scipy | Scientific computing and technical computing
| matplotlib | Plotting library
| pandas | Data manipulation and analysis


## Data Set
- `census_data.csv` - California Census Data
