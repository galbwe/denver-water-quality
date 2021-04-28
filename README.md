# Denver Water Quality

Visualization and easy access of Denver Water Quality Data provided by the Department of Environmental Health


# Data Analysis

Jupyter notebooks for performing exploratory data analysis on data sources.

## Setup
1. Make sure you have a recent version of Python installed on your system. You can check with `python --version`. Notebooks have been verified to run for versions >= 3.9. Versions 3.7 and 3.8 should also be okay, but your mileage may vary. If you have no preference for how to install python, a good way to do it is with [pyenv](https://github.com/pyenv/pyenv). Another option is to directly install python from the [official download page](https://www.python.org/downloads/)
1. Change directories to `data_analysis`: `cd data_analysis`.
1. Create a virtual environment in the `data_analysis` directory with `python -m venv --prompt data_analysis venv`.
1. Activate the virtual environment: `source venv/bin/activate`.
1. Upgrade pip: `pip install --upgrade pip`
1. Install dependencies: `pip install -r requirements.txt`
1. Start a Jupyter server: `jupyter notebook`
    - A web browser should automatically open `localhost:8888`. If not, open a browser and go to `http://localhost:8888`.
1. Open an existing notebook in `src/notebooks`, or create a new one.