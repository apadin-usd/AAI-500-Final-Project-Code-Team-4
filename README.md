# Juan Workspace

This branch contains important EDA and statistical analysis on the Housing Price Prediction dataset ().

The main key features of this datasets are bathrooms, stories, amenities, air conditioning and parking, information on furnishing status. 

The following would be added to this branch:
    - Add the data file and notebooks folder, where we
    would store the dataset; alongside the statistical analyses.
    - Perform descriptive statistics of each of the features
    - Perform bootstrap to calculate an estimated sampling
    distributions of each of the features.
    - Create confidence intervals for each of the features (either using z or t distribution).

# Data file
The dataset we will be working from is here: (https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction).

For now, we have a .gitignore file ignoring the dataset; in the future would be considered to be added to the project; or each member must download it and add it to the data folder.

### Python environments

Make sure you have a compatible python version=3.11.3; installed in your system.
Once installed, open up your terminal (or IDE, like Visual Studio Code).
Install the environment from the specified environment file:

    python --version
    python -m venv venv
    Select the python interpreter
    .\venv\Scripts\activate
    ctrl+shift+p to select interpreter venv python.
    pip install -r .\requirements.txt

After you install, install jupyter kernel inside the venv:

    pip install ipykernel