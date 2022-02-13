# Circuit level implementation of the Reduced Quantum Genetic Algorithm using Qiskit

## Required tools

* Anaconda
* pip
* lapack
* numpy
* networkx
* qiskit - latest version


## Environment setup (Windows & Linux)

* Install **Anaconda**
* Create a minimal environment with **Python version 3.9.7** using `conda create -n ENV_NAME python=3.9.7`
* Activate the environment using `conda activate ENV_NAME`
* Install **pip** using `conda install -c anaconda pip`
* Install **lapack** using `conda install -c conda-forge lapack`
* Install **numpy** using `pip install numpy`
* Install **networkx** using `pip install networkx`
* Install **qiskit** using `pip install qiskit`. Documentation is available [HERE](https://qiskit.org/documentation/getting_started.html)
* Install **jupyterlab** using `pip install jupyterlab`. Documentation is available [HERE](https://jupyter.org/install).

## IBM-Q Account

* Create an account on [https://quantum-computing.ibm.com/](https://quantum-computing.ibm.com/)

## Access systems with IBM-Q account 

* Activate the newly created environment and start python REPL (type `python` in command line).
* In [https://quantum-computing.ibm.com/](https://quantum-computing.ibm.com/) go to `Account settings` and copy the the `API Token`
* In command line, enter the following code:

```python
from qiskit import IBMQ
IBMQ.save_account("TOKEN")
```
More information is available [HERE](https://quantum-computing.ibm.com/lab/docs/iql/manage/account/ibmq)

## Running the simulations

* Start jupyter notebook by running `jupyter notebook` in command line.
* Execute each cell from `rqga_knapsack_problem.ipynb`
