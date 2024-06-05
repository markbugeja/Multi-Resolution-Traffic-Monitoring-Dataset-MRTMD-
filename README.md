# Multi Resolution Traffic Monitoring Dataset (MRTMD)

<!-- <p align="right" style="text-align: right;">
  <strong>"a travel-themed dataset containing 120 different instances organized in a selection of scenes"</strong>
</p>
<br>
<p align="left" style="text-align: left;">
  <strong>"a multipurpose RGB-D dataset that enables the evaluation of a pipelined solution"</strong>
</p> -->


## Abstract
<p align="justify">
<i>
</i>
</p>

## Accessing Dataset
To access this dataset, kindly use the following code:

```python
# Packages Install
!pip install gitpython
import git
import shutil
import os

# Cloning repository
repo_url = 'https://github.com/markbugeja/Multi-Resolution-Traffic-Monitoring-Dataset-MRTMD-.git'
repo_dir = 'MRTMD'  # Directory to clone the repository into

# Checking if the repository directory already exists
if not os.path.exists(repo_dir):
    # Cloning repository
    git.Repo.clone_from(repo_url, repo_dir)
    print("Repository cloned successfully.")
else:
    print("Repository already cloned.")

```

<!-- ## Citation
To cite this paper, kindly use the following citation:

```bib

```

The paper associated with the COTS dataset is available for free as an open-access paper on IEEE: https://ieeexplore.ieee.org/document/9340352 -->

