# SSL-Project

## Virtual Environment

### Creating a Virtual Environment
To create a virtual environment use the following commands in the terminal for this directory:

`python3 -m venv myvenv`

Mac:
`source myvenv/bin/activate`

Windows:
`source .\myvenv\Scripts\activate`

If you see a conda environment is active (i.e. there are 2 sets of things inside parenthesis in front of your terminal username, type
`conda deactivate` so that you just see myvenv as active.

### Adding/Removing Dependencies
Add the names of all libraries to the requirements.txt file on a separate line. Install them by typing the following into the terminal:

`pip install -r requirements.txt`

This will allow us to all have the same dependencies (numpy, scipy, torch, etc).
