# CINECA/IFAB Practical Quantum Computing School 2021
Pasqal's tutorials for the CINECA/IFAB Practical Quantum Computing School 2021.

## Installation

### Step 0 (Optional): Create a clean virtual environment with Python >= 3.7

Creating a virtual environment called `pulser-env` with Python 3.9, using `conda` (recommended):

```
conda create -n pulser-env python=3.9
```

After the new environment is created, activate it by running:

```
conda activate pulser-env 
```

### Step 1: Install Pulser with `pip`

Install the latest release of `pulser` by running:

```
pip install pulser
```

### Step 2: Install Jupyter Notebook

We'll need Jupyter Notebook to run the tutorials, so we run:

```
pip install notebook
```

#### Step 2.1: Adding the new environment to Jupyter notebook

If you created a new virtual environment, you'll need to add it as a new kernel in Jupyter notebook. To do so, we use `ipykernel`:

```
python -m ipykernel install --user --name=pulser-env
```
We now have a new kernel called `pulser-env` inside.

### Step 3: Clone and enter the repository

We now clone the repository with the tutorials (do this inside the folder you desire to place it):

```
git clone https://github.com/pasqal-io/CINECAxIFAB-PQCS.git
cd CINECAxIFAB-PQCS
```
### Step 4: Executing the tutorials

Finally, we launch Jupyter notebook:

```
jupyter notebook
```
After opening a tutorial, make sure the kernel is set to `pulser-env` (or wherever you installed `pulser` in).
