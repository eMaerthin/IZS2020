# IZS2020

## Git Large File Storage
[git lfs](https://git-lfs.github.com/) should be used to store big files.
Please follow [instructions](https://help.github.com/en/github/managing-large-files/installing-git-large-file-storage) to set up git-lfs on your end.

As of now the following paths are tracked with git-lfs:

- `notebooks/*.ipynb`

If you need to track different paths, please add them using git lfs track [path-to-be-tracked]. This will append new lines to .gitattributes file.

## Initiate project

1. Step: Create virtualenv, if `venv` is a good name, you can run this:
`python3 -m venv venv`

2. Step: Activate virtualenv
`source venv/bin/activate`

3. Step: Install dependencies 
`pip install -r requirements.txt`

## Accessing notebooks
After making sure you've initiated project properly, in your terminal run 
`jupyter notebook`

This command should open new instance of jupyter in your browser. It should also display a notification how to access the notebook just in case you accidentally closed it.

In your browser go to `notebooks` directory and open existing file or create your own.
