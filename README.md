# Setup
Use the following command to first create a virtual environment (or use vscode-UI to do so)
```bash
python -m venv .venv
```
Install requirements with:
```bash
pip install -r requirements.txt
```

> [!WARNING]
> First go into the `dummy.py` file and select the correct python-venv as interpreter. Only then will you be able to select it in the jupyter notebook! (Bug of vscode).

# Error calculation
The file 'error_calculation.ipynb' steps through and makes some plots on how accurate you can actually exert a specific force vector on a participant, assuming certain positional tolerances. For the exact math behind it, I might have used a slightly different convention than you did (variable names).
Look at it and ask if I should modify/add anything.

# Data annotation
Annotated data is in the `data` folder. 
An import script is provided with the `import_annotated_data.ipynb` file.

# Selected videos
In the `videos` folder you can find cut and selected videos. They are meant to be watched in a continuous looping manner (e.g. in ppt this can be set).

# Images from videos
With 'extract_images_from_mp4.ipynb' you can easily extract images from any video file.
How-to is described in one of the first cells.

The examples included there are sections I deem worth extracting, but you can of course add other files/sections easily.