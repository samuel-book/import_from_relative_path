# import_from_relative_path

Demo to show how to import a module from a package in a different directory.

In this demo, a Jupyter Notebook, `test.ipynb` in the folder `notebooks` needs to retrieve a module `helper.py` from the folder `utils`, which sits in the main project folder.

Remember that the package folder (`utils` here) needs to contain a file called `__init__.py`. This is commonly empty, or may contain code to run when the package is accessed.
