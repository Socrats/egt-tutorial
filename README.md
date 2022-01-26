# egt-tutorial
Simple tutorial on evolutionary game theory

## Requirements

You need to install EGTtools and Jupyter, for that you need to have Python 3.7 or higher. If you are using Mac with
and M1 processor you should install everything in an Anaconda environment, since the only Scipy version which supports
this processor is available there.

To install all required packages, you can run:

```bash
python -m venv egtenv
source cgtenv/bin/activate
pip install -r requirements.txt
```

Or with anaconda:

```bash
conda create --name cgtenv
conda activate egtenv
pip install -r requirements.txt
```

You should also have `Jupyter` installed to be able to run the notebooks.