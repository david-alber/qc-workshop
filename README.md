# Quantum Computing Workshop

This repository provides skeleton notebooks for the hands-on quantum computing with Qiskit using IBM Quantum devices. 

You are encouraged to fill out the code cells that are marked with the following comment:

```python
# Your code goes here
...
```

For active participation a [IBM Quantum Platform](https://quantum.ibm.com/) (IQP) account is required. 
This account will enable you to execute the Quantum circuits on real IBM Quantum devices.
The account is available to everyone and is completely free of charge.

**Ways to participate:**

Copy your personal IQP API Token to the `api_key_template.txt` file and change its name to `api_key.txt`

* Execution via IQP hosted compute with preset environment:
  1) Upload the jupyter notebooks to the [IBM Quantum Platform Lab](https://lab.quantum.ibm.com/).

* Local execution via jupyter:
  
  1) Create a virtual environment 
    ```sh
    python3 -m venv qiskit_env
    source qiskit_env/bin/activate
    python3 -m pip install -r requirements.txt
    python3 -m ipykernel install --name “qiskit_env”
    ````

  2) Start a jupyter-lab session
    ```sh
    jupyter lab
    ```

  3) Choose the newly created kernel in your jupyter notebook session.