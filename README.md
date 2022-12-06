# impedance_control

This contains a single python notebook that contains a worked out example given in the tutorial [here](https://www.cambridge.org/core/journals/robotica/article/tutorial-survey-and-comparison-of-impedance-control-on-robotic-manipulation/4C93E5D0778D23E0F9DDDA36E5E86C9E).

To run this notebook, you will have to install jupyter notebook and some other dependencies.
The recommended way is to install python virtual environment and then install the dependencies in that.


## Optional step

Follow the instructions [here](https://virtualenvwrapper.readthedocs.io/en/latest/install.html) to setup the virtual environment

```bash
export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
source /usr/local/bin/virtualenvwrapper.sh
```

## Step

In your terminal run the following to install all dependencies.

```
cd impedance_control
pip3 install -r requirements.txt
```

Then open the notebook by typing:

```
jupyter notebook
```

This  will open a session will get some messages in the terminal as shown below.

![Alt text](jupyter_terminal.png?raw=true "JupyterTerminal")


Click on the link that looks similar to 

```
http://localhost:8888/?token=0b1683d04fb85aaa248c146ad55b483d1e697b84bb7d4267
```

This will open your browser to see the notebook as shown below:

![Alt text](session.png?raw=true "Session")

Click on the impedance_control.ipynb file to open it in the browser.