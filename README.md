![image](https://github.com/user-attachments/assets/fb316be9-be46-4c4a-8a80-8cd0c3cc310f)

## What is NumPy?
NumPy is a Python library used for working with arrays.

It also has functions for working in domain of linear algebra, fourier transform, and matrices.

NumPy was created in 2005 by Travis Oliphant. It is an open source project and you can use it freely.

NumPy stands for Numerical Python.

## Why Use NumPy?
In Python we have lists that serve the purpose of arrays, but they are slow to process.

NumPy aims to provide an array object that is up to 50x faster than traditional Python lists.

The array object in NumPy is called ndarray, it provides a lot of supporting functions that make working with ndarray very easy.

Arrays are very frequently used in data science, where speed and resources are very important.

## Why is NumPy Faster Than Lists?
NumPy arrays are stored at one continuous place in memory unlike lists, so processes can access and manipulate them very efficiently.

This behavior is called locality of reference in computer science.

This is the main reason why NumPy is faster than lists. Also it is optimized to work with latest CPU architectures.

## Which Language is NumPy written in?
NumPy is a Python library and is written partially in Python, but most of the parts that require fast computation are written in C or C++.

## Where is the NumPy Codebase?
The source code for NumPy is located at this github repository https://github.com/numpy/numpy

## Installation of NumPy
If you have Python and PIP already installed on a system, then installation of NumPy is very easy.

Install it using this command:

    C:\Users\Your Name>pip install numpy
If this command fails, then use a python distribution that already has NumPy installed like, Anaconda, Spyder etc.

## Import NumPy
Once NumPy is installed, import it in your applications by adding the import keyword:

    import numpy
Now NumPy is imported and ready to use.

## NumPy as np
NumPy is usually imported under the np alias.

alias: In Python alias are an alternate name for referring to the same thing.

Create an alias with the as keyword while importing:

    import numpy as np
Now the NumPy package can be referred to as np instead of numpy.
