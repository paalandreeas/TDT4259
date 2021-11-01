# TDT4259

## Requirements

- [Conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

## Managing environment

### Creating environment

Run `conda env create --name <INSERT_ENV_NAME> -f environment.yml`

[Instructions](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)

### Updating environment

If you have installed any new dependencies, before commiting changes to any branch, run the command `conda env export --from-history > environment.yml`.
