# Starter Kit for ML with Molecular Data

This is the code that I demonstrated during talk I gave in the Molecular Simulations Class (CHE596). These ipython notebooks are an example of an end-to-end ML workflow which includes the following steps:

1. Data Collection (get_data.ipynb) & Curation (clean_data.ipynb)
2. Feature Representation (generate_features.ipynb)
3. Model Training & Evalutation (train_model.ipynb)
4. Model Explanation (with_chemml.ipynb)

## Installation

To run all these you need to create a conda environment and install the necessary packages. Follow the steps below:

1. Install [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) if you haven't already.

2. Open a terminal.

3. Create a new conda environment. Replace `envname` with the name you want to give to your environment:

```bash
conda create --name envname python=3.12
```
4. Activate the conda environment:

```bash
conda activate envname
```

5. Clone this repository and navigate to it:

```bash
cd path/to/your/project
```

6. Install the necessary packages using pip:

```bash
pip install -r requirements.txt
```

7. To run the 'with_chemml.ipynb' notebook, go to https://hachmannlab.github.io/chemml/#installation-and-dependencies to install ChemML's dependencies. 

## Acknowledgment
I would like to acknowledge Dr. Patrick Walters. Some of this code here has been taken from his invaluable Practical Cheminformatics Tutorials(https://github.com/PatWalters/practical_cheminformatics_tutorials). 