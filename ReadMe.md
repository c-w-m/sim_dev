# ![mdf-logo](doc/img/mdf-logo100x100.gif) Simulation Development

> Note: The following projects are based on opens source tools and free 
> services.

#### Table of Contents
* [Setup](#markdown-header-setup)

This project is a collection of open source tools used for creating python simulations.

## Setup
`tox` is the preferred virtual environment management tool when not behind a proxy.  When working behind a `proxy` it may be more convenient to use Anaconda.

### Create a Python Virtual Environment
To create an environment named `eda_dev39` with python 3.9:

#### Using Conda
Using the channel conda-forge and the [requirements.ubnt1604.txt](requirements.ubnt1604.txt) or [requirements.win10.txt](requirements.win10.txt) list of packages:
```shell
# activate conda base
$ conda activate base
(base)$ conda create -y --name sim_dev39 python=3.9
(base)$ conda install --force-reinstall -y -q --name eda_dev39 -c anaconda -c conda-forge -c defaults --file requirements.<os>.txt
(base)$ conda activate sim_dev39
(sim_dev39)$ conda install <any missing packages>
...
(sim_dev39)$ deactivate
(base)$
```
Additional commands can be found in the [cheet-sheets.pdf](doc/conda/conda-cheatsheet.pdf).

### Download the Project Code
Use `clone -- recursive` to get the submodule code.
```shell
$ git clone --recurse-submodules https://github.com/c-w-m/sim_dev.git  ## https or
$ git clone --recurse-submodules git@github.com:c-w-m/sim_dev.git      ## ssh
```

## Directory Layout
| Directory      | Description            |
|----------------|------------------------|
| docs/*         | links and notes        |
| ipynb/*        | demo notebooks         |
| src/*          | submodules             |

## Submodules
The following open-source projects were forked to allow experimental changes without formal pull request review in the source repository.

```shell
$ cd src
$ git submodule add https://github.com/c-w-m/desmod.git
$ git submodule add https://github.com/c-w-m/sympy.git
```

#### Removing Submodules
```shell
# Remove the submodule entry from .git/config
git submodule deinit -f src/<submodule_name>

# Remove the submodule directory from the super-project's .git/modules 
directory
rm -rf .git/modules/src/<submodule_name>     #nix
rd /s /q '.git\modules\src\<submodule_name>' #win

# Remove the entry in .gitmodules and remove the submodule directory located at path/to/submodule
git rm -f src/<submodule_name>
```

## Forked Projects
These are in `src/`

| Directory  | Description            |
|------------|------------------------|
| desmod     | Discrete Event Simulation (based on sympy)|
| simpy      | discrete-event simulation library |

## Jupyter Notebooks
Remember to use `ipykernel` to expose your python environment in Jupyterlab.
```shell
$ conda activate eda_dev39
(sim_dev39)$ python -m ipykernel install --user --name=sim_dev39
(sim_dev39)$ jupyter lab
```

#### List All Kernels
```shell
$ jupyter kernelspec list
```
#### Remove a Kernel
```shell
$ jupyter kernelspec uninstall <kernel_name>
```

## Anaconda Environment
### Create and Load Conda Environment From `yml` File
>Note: The `<os>` designation is either `ubnt1604` (for Ubuntu 16.04) or `win10` (for Windows 10).
```shell
(base)$ conda env create -f eda_dev39.<os>.yml
(base)$ conda activate eda_dev39 
(sim_dev39)$ cd ipynb
(sim_dev39)$ jupyter lab
```

### Install New Conda Environment Packages
```shell
(sim_dev39) $ conda install <package name>
```

### Update Conda Environment Packages
```shell
(sim_dev39) $ conda update <package name>
```

### Export Conda Environment
```shell
(sim_dev39) $ conda env export > sim_dev39.<os>.yml
```

### Get Conda Environment
```shell
(sim_dev39) $ conda info -e
```

### Remove Conda Environment
```shell
(sim_dev39) $ conda remove -n <env_name> -all
```

