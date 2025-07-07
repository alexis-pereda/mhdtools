# A tools collection for MHD/RAW files

## Dependencies

Python packages:
- `click`
- `SimpleITK`
- `scipy`
- `numpy`
- `matplotlib`

## Installation

A python virtual environment is advised:
```sh
# move somewhere you want your environment to be
python -m venv mhdtools
source mhdtools/bin/activate
pip install -U pip
pip install click SimpleITK scipy numpy matplotlib
```

## Helper script

To avoid having to source the python environment manually,
one can write this helper script:

```sh
#!/usr/bin/bash

source /path/to/mhdtools/bin/activate
/path/to/mhdview "$@"
```

To do:
- name the script below `mhdview`
- adapt paths to your installation (env and `mhdview`)
