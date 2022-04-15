# Optimizing Quantum Circuits using ZX Calculus
## PyZX examples

This repo contains the example calculations for my bachelor thesis of the aforementioned title
in the form of Jupyter Notebooks.

### Execution

If you want to clone and execute the Notebooks yourself, you need to install

* Python,
* Jupyter Notebook or JupyterLab,

as well as the following Python packages:

* `pyzx`
* `qiskit[visualization]`

#### Example using virtual environment

To contain a custom Python installation for this repo, you can set up the following environment:

```sh
python3 -m venv env       # Create virtual environment "env"
source ./env/bin/activate # Activate the created virtual environment
pip install pyzx          # Install pyzx in the virtual environment
pip install 'qiskit[visualization]'
                          # Install qiskit for quantum circuit visualization
pip install jupyterlab    # Install JupyterLab
jupyter-lab               # Start JupyterLab, will open in your default browser
```

If you want to use interactive ZX diagram widgets, remember to select
"Help" -> "Launch Classic Notebook"
inside Jupyter Lab,
as they are not supported in the new JupyterLab interface.

You can, of course, also use any other Python virtual environment managers, such as `conda`.
Refer to their respective documentation for how to install `pyzx` and `qiskit`.
