
Analyse_spreadsheet.py is a script where the main par of the code is define in function main.
The 2 other functions (mean_temperature and get_spreadsheet_columns) are of use in order to deal with the initial data and work out the main temperature


### Temperature analysis in spreadsheets

A python script for the analysis of temperatures in excel files.

### Why should I use this project ?

It makes it easy to analyse excel files with temperatures in them.


### Setup

You need `python>3.5` to run this script.

The project depends on the `pandas` library, install it with pip:
`pip install pandas`


### How to run?

You can run the script from the command-line using
```
python analyse_spreadsheet.py
```

You can use functions directly, for example: calculate the mean temperature of some data:
```python
from analyse_spreadsheet import mean_temperature

print(mean_temperature(data))
```

