# Python Pandas Package Documentation

Welcome! This is the documentation for our **PPP** Python library emulating a Pandas package.
The aim of this package is to create a Python library with a simplified DataFrame object.

## Documentation

This package is based on NumPy, the Python library for fast numeric array computations.

## Special Methods  
### __init__
The `__init__` speciql method allows support for integers, floats, booleans and non-numerical string columns.  
To be initalized it must consist of a dictionnary of NumPy arrays or a list. It must have a consistent number of rows to work.  

### __repr__
The `__repr__` special method allows for a nicer output.

### __getitem__
The `__getitem__` special method allows for a dictionary-style access to columns (`df["col_name"]`).

### __setitem__
The `__setitem__` special method allows read and write actions, defining the behavior for when an item is assigned to.  

### .get_row()
This function allows you to access individual entries corresponding to the row  

## Arithmetic Operators  
The Arithmetic Operators work through the use of the `aggFunction`. This function serves to replicate its functionalities accross the different arithmetic functions.   
### .sum()  
This function computes the summed value of the NumPy array  
### .median()  
This function computes the median value of the NumPy array  
### .min()  
This function computes the minimum value of the NumPy array  
### .max()  
This function computes the maximum value of the NumPy array  
### .var()  
This function computes the variance of the NumPy array  
### .std()  
This function computes the standard deviation of the NumPy array  
### .argmin()
This function returns the indices of the minimum values of the NumPy array  
### .argmax()
This function returns the indices of the maximum values of the NumPy array  



-----------
## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

For full documentation visit [mkdocs.org](https://mkdocs.org).
