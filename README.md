# Example Package

This is a simple example package. 

## Installation
### Linux
requirements: python3 and pip3

* create an virtual environment and activate it
    python3 -m venv venv
    source venv/bin/activate

* install package
    pip install --upgrade wheel
    pip install https://github.com/losgehts/pkg-test/archive/master.zip

that's it!

## Test the package
* start the virtual environment (if not already)
    source venv/bin/activate

* start python console
    python3
    
* and:
    >>> from example_pkg.mmodule import my_func
    >>> my_func()
    'Hallo Welt!'

