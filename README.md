<img src="figures/sc1.gif" alt="GIF" width="250" height="250">      <img src="figures/giphy_ev.gif" alt="https://giphy.com/gifs/araldeutschland-charging-aral-electriccar-IaVWq3MSU6EMsVCTkz" width="250" height="250">     <img src="figures/sc2.gif" alt="GIF" width="250" height="250">

# UL-Flexibility [![DOI](https://zenodo.org/badge/771205916.svg)](https://zenodo.org/doi/10.5281/zenodo.10811009)

![Static Badge](https://img.shields.io/badge/MADE_WITH-PYTHON_%26_MATLAB-orange?style=for-the-badge)

[![matplotlib](https://img.shields.io/badge/matplotlib-3.5.1-blue.svg)](https://pypi.org/project/matplotlib/3.5.1/)
[![numpy](https://img.shields.io/badge/numpy-1.22.3-blue.svg)](https://pypi.org/project/numpy/1.22.3/)
[![pandas](https://img.shields.io/badge/pandas-1.4.3-blue.svg)](https://pypi.org/project/pandas/1.4.3/)
[![psutil](https://img.shields.io/badge/psutil-5.9.0-blue.svg)](https://pypi.org/project/psutil/5.9.0/)
[![psutil](https://img.shields.io/badge/psutil-5.9.1-blue.svg)](https://pypi.org/project/psutil/5.9.1/)
[![Pyomo](https://img.shields.io/badge/Pyomo-6.4.2-blue.svg)](https://pypi.org/project/Pyomo/6.4.2/)
[![scipy](https://img.shields.io/badge/scipy-1.7.3-blue.svg)](https://pypi.org/project/scipy/1.7.3/)
[![tqdm](https://img.shields.io/badge/tqdm-4.62.3-blue.svg)](https://pypi.org/project/tqdm/4.62.3/)
[![Gurobi Version](https://img.shields.io/badge/Gurobi-10.0.2-blue.svg)](https://www.gurobi.com/)

This repository contains the codes and results which is published in the [paper](https://arxiv.org/abs/2310.02729) title: **"Efficient Quantification and Representation of Aggregate Flexibility in Electric Vehicles"** by [Nanda Kishor Panda](https://github.com/nkpanda97) and [Simon Tindemans](https://github.com/simontindemans).

<inkline>
  <picture>
    <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
    <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="25" height="25">
  </picture>
</inkline> <span style="font-size:1.8em;font-style:italic">Highlights</span>

&#x2705; Exact aggregation of flexibility for a large number of Electric Vehicles (EVs) 🚗 🚙  <br>
&#x2705; Additive minkowski summation for flexibility aggregation <br>
&#x2705; Efficient representation of feasible flexibility of EVs <br>
&#x2705; Function to plot 3-d Polytopes using MATLAB <br>

## File organization

The repository is organized as follows:

- 📁 [data](data/): Contains the data used in the paper
- 📁 [figures](figures/): Contains the figures used in the paper
- 📁 [matlab_functions](matlab_functions/): Contains the MATLAB functions used to generate 3-d polytope
- <img src="figures/image.png" alt="python logo" width="15" height="15"> [helper_functions.py](helper_functions.py): Contains all helper functions used in the rest of the code.
- <img src="figures/image.png" alt="python logo" width="15" height="15"> [run_me.ipynb](main.py): Contains the main code to run the results of the paper and other functions.
- [.gitignore](.gitignore): Contains the files to be ignored by git
- [LICENSE](LICENSE): Contains the license information


## Installation

***Step 1:*** Clone the repository

```bash
git clone <repo-link>
```

***Step 2:*** Install the required packages
The code is tested on [![Python Version](https://img.shields.io/badge/Python-3.10.13-blue.svg)](https://www.python.org/downloads/release/python-3812/). The required packages are listed in the [requirements.txt](requirements.txt) file. To install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

or

```bash
conda install --file requirements.txt
```

For the optimization solver, we used [![Gurobi Version](https://img.shields.io/badge/Gurobi-10.0.2-blue.svg)](https://www.gurobi.com/)
. You can install the Gurobi solver by following the instructions in the [Gurobi Documentation](https://www.gurobi.com/documentation/10.0/quickstart_mac/installing_the_anaconda_py.html) for Mac and Linux and [Gurobi Documentation](https://www.gurobi.com/documentation/10.0/quickstart_windows/installing_the_anaconda_py.html) for Windows.

> **Note** The results presented for computational performance is based on the program being run on a machine configuration featuring the Apple M2 MAX chip with 12-core CPU, macOS Ventura Version 13.5.1, 32GB RAM, in conjunction with Python 3.10.11 and the Gurobi 10.0.2 optimization solver.

## Cite this work

If you liked this work and want to use it in your research, please consider citing the original paper:

The paper can be found at [arXiv](https://arxiv.org/abs/2310.02729)

```bibtex
@misc{panda2023efficient,
      title={Efficient Quantification and Representation of Aggregate Flexibility in Electric Vehicles}, 
      author={Nanda Kishor Panda and Simon H. Tindemans},
      year={2023},
      eprint={2310.02729},
      archivePrefix={arXiv},
      primaryClass={eess.SY}
}
```

If you re-use part of the code or some of the functions, please consider citing the repository:

```bibtex  
@software{nanda_kishor_panda_2024_10811010,
  author       = {Nanda Kishor Panda},
  title        = {nkpanda97/ul-flexiility: Version 0},
  month        = mar,
  year         = 2024,
  publisher    = {Zenodo},
  version      = {pre-release},
  doi          = {10.5281/zenodo.10811010},
  url          = {https://doi.org/10.5281/zenodo.10811010}
}

```

## Funding

The research was supported by the [ROBUST](https://tki-robust.nl/) project, which received funding from the MOOI subsidy programme under grant agreement MOOI32014 by the Netherlands Ministry of Economic Affairs and Climate Policy and the Ministry of the Interior and Kingdom Relations, executed by the Netherlands Enterprise Agency. The authors would like to thank ROBUST consortium partners for fruitful discussions during the preparation of this paper
