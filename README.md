# BAC bus trailer count

## Installation

First you need to clone the Repository
In order to use the project you need to install the following tools :

- [Python 3.7](https://www.python.org/downloads/)
- [MiniConda](https://docs.conda.io/en/latest/miniconda.html) (This one will install Python as well)

Then open a terminal at the root of the project and type :

```
## This command will create the Python environment
> conda env create -f environment.yml

## This command will activate it
> conda activate BacTrailer
```

## Usage

If you want the help you can type 
```
Python parse.py --help
```

This will show this message :

```
usage: parse.py [-h] -f [-s] [-e]

Get the trailer kms 

optional arguments: 
    -h, --help        show this help message and exit
    -f , --filename   path to file to parse
    -s , --start      date to start parsing (DD/MM/YYYY)
    -e , --end        date to finish parsing (DD/MM/YYYY)
```