# RePEc-Python-Scripts
Python scripts to work with ReDIF format
http://econpapers.repec.org/software/rpcscript/

## Requirements 
1. Python 2.7: https://www.python.org/download/releases/2.7/ (pre-installed on on most Mac OS and Linux versions)
2. git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git (optional)

## Download
* Download the repository in a zip format and unzip it on your computer 

Or
* git clone https://github.com/moqri/RePEc-Python-Scripts.git

## Preperation
Put your ReDIF file(s) in your local RePEc-Python-Scripts directory


## Convert ReDIF to JSON-LD (http://json-ld.org/)
In a Command Line Terminal type 
* python redif2jsonld.py

## Convert ReDIF to Python DataFrame - Pandas 
### Requirement 
1. pandas (http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.html)

In a Command Line Terminal type 
* python redif2df.py

## Convert ReDIF to CSV Table
### Requirement 
1. pandas (http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.html)

In a Command Line Terminal type 
* python redif2csv.py

## Example
See the notebook:
https://github.com/moqri/RePEc-Python-Scripts/blob/master/redif2jsonld.ipynb

