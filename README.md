[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luyihappy/BERN02_challenge_project/blob/main/retention_time.ipynb)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)


# The final project of BERN02: Modelling with dimension reduction guided by Lasso regression in predicting the molecular retention time in liquid chromatography



## Layout

Description of the directory layout.

- `README.md` This is the file you're viewing right now.
- `image folder` This folder has saved an image that shows why the non-retained compounds should be dropped from the dataset.
- `SMRT_ECFP_1024_Fingerprints.zip` This is input variables dataset.
- `SMRT_data.csv` This is target variables dataset.
- `retention_time.ipynb`  This is the jupyter notebook document of the retention time regression.
- `requirements.txt`  This is the document that records the version of libraries in python.
  
## Environments
- Python： 3.13.0
- Environment manager: venv

## Requirements

To run the Notebooks online, click on the _Open in Colab_ badge above. Alternatively, to run on your own computer, create a virtual environment
and use python version  3.13.0 as the environment. The required Python libraries and their versions are listed in requirements.txt.

``` bash
python -3.13.0 -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```


## Risk assessment

The code might not be usable in the future package breaking. The method to solve this problem is to set the code running environment according to the respective versions given in the file 'requirements.txt'.




