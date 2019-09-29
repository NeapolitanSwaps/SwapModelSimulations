# Local Setup
It is recomended that all packages are installed within a python virtual environment if you want to run this notebook locally. This will ensure that packages are not installed to your local environment and makes the execution consistent between machines. This can be done as follows:

Install virtualenv if you dont already have it
```
pip install virtualenv
```

Create the virtual enviroment
```
virtualenv venv -p python3
```

Activate the virtual enviroment. You shell should now say (`venv`) on the left side.
```
source venv/bin/activate
```

Install packages
```
pip install -r requirements.txt
```

Ensure kernel can be accessed by Jupyter
```
python -m ipykernel install --user --name=SwapSimulator
```
Start the notebook.

```
jupyter notebook
```

Now navigate to http://localhost:8888 where you can find the live notebook. From within the notebook your Kernel should be set to SwapSimulator in the top right. If it's not click the Kernel tab and change it to SwapSimulator.
