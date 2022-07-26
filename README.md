# calc-script-find_run_diff

A jupyter notebook wrapper related to finding new runs with different patterns in two folders.

## Requirements
- conda

## Installation
install conda env, recommendation is into project dir
`conda env create -p ./.venv --file ./notebooks/conda.env.yml`

Set the jupyter server to use the conda env
install conda env, recommendation is into project dir by pointing it to`./.venv`

Add associate input and output folders. The default location is `./input` and `./output`,

## Running
To run the notebook form CLI
`papermill ./notebooks/find_run_diff.ipynb -`
This will dump the output to stdout and stderr. Alternatively you can run and define a new notebook which will store associated outputs there.

See notebook for further details.