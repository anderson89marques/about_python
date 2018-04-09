Python Virtual Environment
=========================

Virtual environment in python is the way to isolate dependencies for each project that we create.

From python 3.3 and forth the code below must works.

```console
$ python -m venv myenv
```

"myenv" is the name of the virtual environment.
To activate the virtual environment

```console
$ source myenv/bin/activate
```

The Python version in the virtual environment is the same that you used to create it.

Now you can install you dependencies in your environment using ```pip install```

To deactivate use:

```console
$ source myenv/bin/deactivate
```

Thanks for Read it :D