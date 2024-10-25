# Quantum Computing Workshop

This repository provides skeleton notebooks for hands-on quantum computing with Qiskit using IBM Quantum devices. 

You are encouraged to fill out the code cells that are marked with the following comment:

```python
# Your code goes here
...
```

For active participation a [IBM Quantum Platform](https://quantum.ibm.com/) (IQP) account is required. 
This account will enable you to execute the Quantum circuits on real IBM Quantum devices.
The account is available to everyone and is completely free of charge.

**👨‍💻 Ways to participate: 👩‍💻**

Copy your personal IQP API Token to the `api_key_template.txt` file and change its name to `api_key.txt`


👉 [Binder](https://mybinder.org/) container with preset environment:
  1) Go to [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/david-alber/qc-workshop/main). Everything is set up for you 😉.
  2) Upload your api_key.txt file or copy it in the respective code cell.

👉 Local execution via Jupyter:
  
  1) Download Python [here](https://www.python.org/downloads/) 🐍.
  
  2) Create a virtual environment 
  ```sh
  python3 -m venv qc_workshop
  source qc_workshop/bin/activate
  pip install -r requirements.txt
  python3 -m ipykernel install --name qc_workshop
  ```
  **Note:**
  
   To activate your Python virtual environment on **Windows** use: 
  ```sh
  qc_workshop\Scripts\activate.bat
  ```

  3) Start a Jupyter-Lab session
  ```sh
  jupyter lab
  ```

  4) Choose the newly created kernel in your Jupyter notebook session.