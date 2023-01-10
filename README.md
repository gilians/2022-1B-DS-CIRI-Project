# Set-up

In order to setup your environment, first navigate your terminal to the root of this repository. Then, execute the following:

```bash
conda create -p ./env --file ./requirements.txt
```

The environment needs to be added as a kernel to Jupyter. Hence, still in the root of this repository, do the following:

```bash
# Activate conda environment
conda activate ./env
# Create IPython kernel
python -m ipykernel install --user --name=<any name you like>
```

A kernel with the name you have chosen should now be available in Jupyter. You might have to restart Jupyter first.
